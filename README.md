<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Tech - Cadastro de Cliente</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
        }
        .service-card {
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .service-card:hover {
            transform: translateY(-8px) scale(1.03);
            box-shadow: 0 16px 32px rgba(106, 76, 255, 0.15);
            border-color: #a777e3;
        }
        .animate-pulse {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.07); }
            100% { transform: scale(1); }
        }
        .hero-bg {
            background: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c?auto=format&fit=crop&w=1500&q=80') center/cover no-repeat;
            position: relative;
        }
        .hero-overlay {
            background: rgba(55, 0, 120, 0.55);
            position: absolute;
            inset: 0;
            z-index: 1;
        }
        .hero-content {
            position: relative;
            z-index: 2;
        }
    </style>
</head>
<body class="bg-gray-100 font-sans">
    <!-- Header -->
    <header class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-4 py-6">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <i class="fas fa-laptop-code text-3xl"></i>
                    <h1 class="text-2xl font-bold">Digital Tech</h1>
                </div>
                <nav class="hidden md:block">
                    <ul class="flex space-x-6">
                        <li><a href="#services" class="hover:text-gray-200 transition">Serviços</a></li>
                        <li><a href="#register" class="hover:text-gray-200 transition">Cadastro</a></li>
                        <li><a href="#quote" class="hover:text-gray-200 transition">Orçamento</a></li>
                        <li><a href="#contact" class="hover:text-gray-200 transition">Contato</a></li>
                    </ul>
                </nav>
                <button class="md:hidden text-2xl">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-bg relative text-white py-20">
        <div class="hero-overlay"></div>
        <div class="container mx-auto px-4 text-center hero-content">
            <h2 class="text-5xl font-extrabold mb-6 animate-pulse drop-shadow-lg">Manutenção de Computadores Profissional</h2>
            <p class="text-2xl mb-10 max-w-2xl mx-auto drop-shadow">Soluções tecnológicas personalizadas para sua empresa ou residência</p>
            <a href="#register" class="bg-gradient-to-r from-purple-500 to-blue-500 text-white font-bold py-4 px-10 rounded-full shadow-lg hover:scale-105 transition duration-300 inline-block text-lg">
                Cadastre-se Agora
            </a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Nossos Serviços</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-tools text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-800">Manutenção Preventiva</h3>
                    <p class="text-gray-600">Limpeza interna, troca de pasta térmica, verificação de componentes e otimização do sistema.</p>
                </div>
                
                <!-- Service 2 -->
                <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-bug text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-800">Remoção de Vírus</h3>
                    <p class="text-gray-600">Identificação e remoção de malware, spyware e vírus com ferramentas profissionais.</p>
                </div>
                
                <!-- Service 3 -->
                <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-hdd text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-800">Recuperação de Dados</h3>
                    <p class="text-gray-600">Recuperação de arquivos perdidos em HDs, SSDs, pendrives e outros dispositivos.</p>
                </div>
                
                <!-- Service 4 -->
                <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-network-wired text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-800">Redes e Wi-Fi</h3>
                    <p class="text-gray-600">Configuração e solução de problemas em redes cabeadas e sem fio.</p>
                </div>
                
                <!-- Service 5 -->
                <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-desktop text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-800">Upgrade de Hardware</h3>
                    <p class="text-gray-600">Atualização de componentes para melhorar desempenho do seu computador.</p>
                </div>
                
                <!-- Service 6 -->
                <div class="service-card bg-gray-50 p-6 rounded-lg shadow-md transition duration-300">
                    <div class="text-purple-600 mb-4">
                        <i class="fas fa-cloud text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-2 text-gray-800">Backup em Nuvem</h3>
                    <p class="text-gray-600">Solução segura para backup automático de seus arquivos importantes.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Registration Form -->
    <section id="register" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="gradient-bg text-white py-4 px-6">
                    <h2 class="text-2xl font-bold">Cadastro de Cliente</h2>
                    <p class="text-sm opacity-90">Preencha seus dados para se cadastrar em nosso sistema</p>
                </div>
                <form id="registrationForm" class="p-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <label for="name" class="block text-gray-700 font-medium mb-2">Nome Completo*</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                        </div>
                        <div>
                            <label for="email" class="block text-gray-700 font-medium mb-2">E-mail*</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                        </div>
                        <div>
                            <label for="phone" class="block text-gray-700 font-medium mb-2">Telefone*</label>
                            <input type="tel" id="phone" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                        </div>
                        <div>
                            <label for="cpf" class="block text-gray-700 font-medium mb-2">CPF*</label>
                            <input type="text" id="cpf" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                        </div>
                        <div>
                            <label for="address" class="block text-gray-700 font-medium mb-2">Endereço</label>
                            <input type="text" id="address" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
                        </div>
                        <div>
                            <label for="city" class="block text-gray-700 font-medium mb-2">Cidade</label>
                            <input type="text" id="city" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
                        </div>
                    </div>
                    <div class="mt-6">
                        <label class="flex items-center">
                            <input type="checkbox" class="form-checkbox h-5 w-5 text-purple-600" required>
                            <span class="ml-2 text-gray-700">Aceito os termos de uso e política de privacidade</span>
                        </label>
                    </div>
                    <div class="mt-8">
                        <button type="submit" class="gradient-bg text-white font-bold py-3 px-6 rounded-lg hover:opacity-90 transition w-full md:w-auto">
                            Cadastrar
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Quote Section -->
    <section id="quote" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Solicite um Orçamento</h2>
            <div class="max-w-3xl mx-auto bg-gray-50 rounded-lg shadow-lg overflow-hidden">
                <div class="gradient-bg text-white py-4 px-6">
                    <h3 class="text-xl font-bold">Descreva o problema ou serviço necessário</h3>
                    <p class="text-sm opacity-90">Responderemos em até 24 horas úteis</p>
                </div>
                <form id="quoteForm" class="p-6">
                    <div class="mb-6">
                        <label for="serviceType" class="block text-gray-700 font-medium mb-2">Tipo de Serviço*</label>
                        <select id="serviceType" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                            <option value="" disabled selected>Selecione um serviço</option>
                            <option value="preventiva">Manutenção Preventiva</option>
                            <option value="corretiva">Manutenção Corretiva</option>
                            <option value="virus">Remoção de Vírus</option>
                            <option value="dados">Recuperação de Dados</option>
                            <option value="rede">Problemas de Rede</option>
                            <option value="upgrade">Upgrade de Hardware</option>
                            <option value="outro">Outro</option>
                        </select>
                    </div>
                    <div class="mb-6">
                        <label for="equipmentType" class="block text-gray-700 font-medium mb-2">Tipo de Equipamento*</label>
                        <select id="equipmentType" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                            <option value="" disabled selected>Selecione o equipamento</option>
                            <option value="notebook">Notebook</option>
                            <option value="desktop">Computador Desktop</option>
                            <option value="allinone">All-in-One</option>
                            <option value="servidor">Servidor</option>
                            <option value="outro">Outro</option>
                        </select>
                    </div>
                    <div class="mb-6">
                        <label for="problemDescription" class="block text-gray-700 font-medium mb-2">Descrição do Problema/Serviço*</label>
                        <textarea id="problemDescription" rows="5" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required></textarea>
                    </div>
                    <div class="mb-6">
                        <label for="urgency" class="block text-gray-700 font-medium mb-2">Urgência</label>
                        <select id="urgency" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
                            <option value="normal">Normal (5 dias úteis)</option>
                            <option value="urgente">Urgente (48 horas)</option>
                            <option value="emergencia">Emergência (24 horas)</option>
                        </select>
                    </div>
                    <div class="mb-6">
                        <label for="clientEmail" class="block text-gray-700 font-medium mb-2">Seu E-mail*</label>
                        <input type="email" id="clientEmail" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500" required>
                    </div>
                    <div>
                        <button type="submit" class="gradient-bg text-white font-bold py-3 px-6 rounded-lg hover:opacity-90 transition w-full">
                            Enviar Solicitação
                        </button>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12 text-gray-800">Entre em Contato</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-5xl mx-auto">
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Informações de Contato</h3>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <i class="fas fa-map-marker-alt text-purple-600 mt-1 mr-3"></i>
                            <p>Av. Tecnologia, 1234 - Centro, São Paulo/SP</p>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-phone-alt text-purple-600 mr-3"></i>
                            <p>(11) 1234-5678</p>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-envelope text-purple-600 mr-3"></i>
                            <p>contato@digitaltech.com.br</p>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-clock text-purple-600 mr-3"></i>
                            <p>Segunda a Sexta: 9h às 18h<br>Sábado: 9h às 13h</p>
                        </div>
                    </div>
                    <div class="mt-6">
                        <h4 class="font-medium mb-2">Siga-nos</h4>
                        <div class="flex space-x-4">
                            <a href="#" class="text-purple-600 hover:text-purple-800 text-xl"><i class="fab fa-facebook"></i></a>
                            <a href="#" class="text-purple-600 hover:text-purple-800 text-xl"><i class="fab fa-instagram"></i></a>
                            <a href="#" class="text-purple-600 hover:text-purple-800 text-xl"><i class="fab fa-linkedin"></i></a>
                            <a href="#" class="text-purple-600 hover:text-purple-800 text-xl"><i class="fab fa-whatsapp"></i></a>
                        </div>
                    </div>
                </div>
                <div class="bg-white p-8 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold mb-4 text-gray-800">Mensagem Rápida</h3>
                    <form id="contactForm">
                        <div class="mb-4">
                            <label for="contactName" class="block text-gray-700 mb-2">Seu Nome</label>
                            <input type="text" id="contactName" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
                        </div>
                        <div class="mb-4">
                            <label for="contactEmail" class="block text-gray-700 mb-2">Seu E-mail</label>
                            <input type="email" id="contactEmail" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500">
                        </div>
                        <div class="mb-4">
                            <label for="contactMessage" class="block text-gray-700 mb-2">Mensagem</label>
                            <textarea id="contactMessage" rows="4" class="w-full px-4 py-2 border rounded-lg focus:outline-none focus:ring-2 focus:ring-purple-500"></textarea>
                        </div>
                        <button type="submit" class="gradient-bg text-white font-bold py-2 px-6 rounded-lg hover:opacity-90 transition">
                            Enviar Mensagem
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">Digital Tech</h3>
                    <p class="text-gray-400">Soluções em tecnologia e manutenção de computadores com qualidade e garantia.</p>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Links Úteis</h3>
                    <ul class="space-y-2">
                        <li><a href="#services" class="text-gray-400 hover:text-white transition">Serviços</a></li>
                        <li><a href="#register" class="text-gray-400 hover:text-white transition">Cadastro</a></li>
                        <li><a href="#quote" class="text-gray-400 hover:text-white transition">Orçamento</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition">Contato</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-xl font-bold mb-4">Newsletter</h3>
                    <p class="text-gray-400 mb-2">Assine para receber nossas promoções.</p>
                    <form class="flex">
                        <input type="email" placeholder="Seu e-mail" class="px-4 py-2 rounded-l-lg focus:outline-none text-gray-800 w-full">
                        <button type="submit" class="gradient-bg px-4 rounded-r-lg">
                            <i class="fas fa-paper-plane"></i>
                        </button>
                    </form>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-6 text-center text-gray-400">
                <p>&copy; 2023 Digital Tech. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>

    <!-- Success Modal -->
    <div id="successModal" class="fixed inset-0 bg-black bg-opacity-50 flex items-center justify-center z-50 hidden">
        <div class="bg-white rounded-lg p-6 max-w-md w-full mx-4">
            <div class="text-center">
                <div class="mx-auto flex items-center justify-center h-12 w-12 rounded-full bg-green-100 mb-4">
                    <i class="fas fa-check text-green-600 text-xl"></i>
                </div>
                <h3 id="modalTitle" class="text-lg font-medium text-gray-900 mb-2">Sucesso!</h3>
                <p id="modalMessage" class="text-gray-500 mb-6">Seu cadastro foi realizado com sucesso.</p>
                <button onclick="closeModal()" class="gradient-bg text-white font-bold py-2 px-6 rounded-lg hover:opacity-90 transition">
                    Fechar
                </button>
            </div>
        </div>
    </div>

    <script>
        // Form submission handlers
        document.getElementById('registrationForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Coletar dados do formulário
            const clientData = {
                name: document.getElementById('name').value,
                email: document.getElementById('email').value,
                phone: document.getElementById('phone').value,
                cpf: document.getElementById('cpf').value,
                address: document.getElementById('address').value,
                city: document.getElementById('city').value
            };
            
            // Salvar dados no localStorage
            localStorage.setItem('clientData', JSON.stringify(clientData));
            
            // Mostrar modal e redirecionar após fechar
            showModal('Cadastro realizado!', 'Seu cadastro foi concluído com sucesso. Redirecionando para a página de confirmação...');
            
            // Redirecionar após 2 segundos
            setTimeout(function() {
                window.location.href = 'confirmacao.html';
            }, 2000);
        });

        document.getElementById('quoteForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Coletar dados do formulário
            const serviceData = {
                serviceType: document.getElementById('serviceType').options[document.getElementById('serviceType').selectedIndex].text,
                equipmentType: document.getElementById('equipmentType').options[document.getElementById('equipmentType').selectedIndex].text,
                problemDescription: document.getElementById('problemDescription').value,
                urgency: document.getElementById('urgency').options[document.getElementById('urgency').selectedIndex].text,
                clientEmail: document.getElementById('clientEmail').value
            };
            
            // Salvar dados no localStorage
            localStorage.setItem('serviceData', JSON.stringify(serviceData));
            
            // Mostrar modal e redirecionar após fechar
            showModal('Orçamento solicitado!', 'Recebemos sua solicitação de orçamento. Redirecionando para a página de confirmação...');
            
            // Redirecionar após 2 segundos
            setTimeout(function() {
                window.location.href = 'confirmacao.html';
            }, 2000);
        });

        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            showModal('Mensagem enviada!', 'Sua mensagem foi enviada com sucesso. Retornaremos em breve.');
            this.reset();
        });

        // Modal functions
        function showModal(title, message) {
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalMessage').textContent = message;
            document.getElementById('successModal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('successModal').classList.add('hidden');
        }

        // Mobile menu toggle (would need implementation)
        // CPF mask
        document.getElementById('cpf').addEventListener('input', function(e) {
            let value = e.target.value.replace(/\D/g, '');
            value = value.replace(/(\d{3})(\d)/, '$1.$2');
            value = value.replace(/(\d{3})(\d)/, '$1.$2');
            value = value.replace(/(\d{3})(\d{1,2})$/, '$1-$2');
            e.target.value = value;
        });

        // Phone mask
        document.getElementById('phone').addEventListener('input', function(e) {
            let value = e.target.value.replace(/\D/g, '');
            value = value.replace(/^(\d{2})(\d)/g, '($1) $2');
            value = value.replace(/(\d)(\d{4})$/, '$1-$2');
            e.target.value = value;
        });
    </script>
</body>
</html>
