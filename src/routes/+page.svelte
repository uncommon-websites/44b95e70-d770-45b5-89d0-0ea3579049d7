<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-neon-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Search/Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-neon-primary)]"></span>
                        <span class="text-white text-sm font-medium">30 milhões</span>
                        <span class="text-gray-400 text-sm">de clientes confiam na Neon</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        Transforme suas economias em crédito.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Conta digital 100% gratuita com cartão de crédito sem anuidade. Converta seu CDB em limite de crédito com o Viracrédito e ganhe cashback em todas as compras.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Abrir Conta Grátis
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Conhecer o Viracrédito
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Images/Cards -->
            <div class="mt-20 relative">
                <div class="flex justify-center gap-6 overflow-hidden px-6">
                    <!-- Card 1 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform -rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs text-gray-500">Saldo disponível</div>
                                <div class="h-8 px-3 bg-[var(--color-neon-primary)]/20 rounded text-[var(--color-neon-primary)] text-sm flex items-center justify-center font-bold">R$ 3.847,92</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-20 bg-gradient-to-br from-purple-500 to-blue-600 rounded-lg w-full p-3 text-white flex flex-col justify-between">
                                    <div class="text-xs opacity-80">Cartão Neon</div>
                                    <div class="text-sm font-mono">•••• 4829</div>
                                </div>
                                <div class="flex gap-2">
                                    <div class="flex-1 h-12 bg-gray-50 rounded flex items-center justify-center text-xs text-gray-600">Pix</div>
                                    <div class="flex-1 h-12 bg-gray-50 rounded flex items-center justify-center text-xs text-gray-600">Pagar</div>
                                    <div class="flex-1 h-12 bg-gray-50 rounded flex items-center justify-center text-xs text-gray-600">Transferir</div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 2 (Center) -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 z-10">
                        <div class="bg-white h-full flex flex-col">
                            <div class="bg-gradient-to-br from-purple-600 to-blue-600 p-6">
                                <div class="flex justify-between items-start text-white">
                                    <div>
                                        <div class="text-xs opacity-80 mb-1">Cashback acumulado</div>
                                        <div class="text-2xl font-bold">R$ 127,50</div>
                                    </div>
                                    <div class="w-10 h-10 bg-white/20 backdrop-blur-sm rounded-full flex items-center justify-center">
                                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"/><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z" clip-rule="evenodd"/></svg>
                                    </div>
                                </div>
                            </div>
                            <div class="p-6 flex-grow">
                                <div class="text-xs text-gray-500 mb-3">Últimas transações</div>
                                <div class="space-y-3">
                                    <div class="flex justify-between items-center py-2 border-b border-gray-100">
                                        <div class="flex items-center gap-2">
                                            <div class="w-8 h-8 rounded-full bg-green-100 flex items-center justify-center text-green-600 text-xs">+</div>
                                            <div class="text-xs">Cashback</div>
                                        </div>
                                        <div class="text-xs font-semibold text-green-600">+R$ 12,50</div>
                                    </div>
                                    <div class="flex justify-between items-center py-2 border-b border-gray-100">
                                        <div class="flex items-center gap-2">
                                            <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-gray-600 text-xs">🛒</div>
                                            <div class="text-xs">Supermercado</div>
                                        </div>
                                        <div class="text-xs font-semibold text-gray-900">-R$ 250,00</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Card 3 -->
                    <div class="w-[350px] md:w-[450px] flex-shrink-0 rounded-xl overflow-hidden shadow-2xl border border-white/10 transform rotate-2 mt-8">
                        <div class="bg-white p-4">
                            <div class="flex items-center justify-between mb-4">
                                <div class="text-xs text-gray-500">CDB Neon</div>
                                <div class="h-8 px-3 bg-green-100 rounded text-green-700 text-sm flex items-center justify-center font-bold">113% CDI</div>
                            </div>
                            <div class="space-y-3">
                                <div class="h-20 bg-gradient-to-br from-green-50 to-blue-50 rounded-lg w-full p-3 flex flex-col justify-between border border-green-100">
                                    <div class="text-xs text-gray-600">Investimento total</div>
                                    <div class="text-xl font-bold text-gray-900">R$ 5.200,00</div>
                                </div>
                                <div class="text-xs text-gray-500 text-center">Rendendo mais que a poupança</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Trust Indicators Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 text-gray-400">
                    <div class="flex items-center gap-2">
                        <svg class="w-6 h-6 text-[var(--color-neon-primary)]" fill="currentColor" viewBox="0 0 20 20"><path d="M9 6a3 3 0 11-6 0 3 3 0 016 0zM17 6a3 3 0 11-6 0 3 3 0 016 0zM12.93 17c.046-.327.07-.66.07-1a6.97 6.97 0 00-1.5-4.33A5 5 0 0119 16v1h-6.07zM6 11a5 5 0 015 5v1H1v-1a5 5 0 015-5z"/></svg>
                        <span class="text-sm font-medium">30M+ usuários</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-6 h-6 text-[var(--color-neon-primary)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M6.267 3.455a3.066 3.066 0 001.745-.723 3.066 3.066 0 013.976 0 3.066 3.066 0 001.745.723 3.066 3.066 0 012.812 2.812c.051.643.304 1.254.723 1.745a3.066 3.066 0 010 3.976 3.066 3.066 0 00-.723 1.745 3.066 3.066 0 01-2.812 2.812 3.066 3.066 0 00-1.745.723 3.066 3.066 0 01-3.976 0 3.066 3.066 0 00-1.745-.723 3.066 3.066 0 01-2.812-2.812 3.066 3.066 0 00-.723-1.745 3.066 3.066 0 010-3.976 3.066 3.066 0 00.723-1.745 3.066 3.066 0 012.812-2.812zm7.44 5.252a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                        <span class="text-sm font-medium">Autorizado pelo Banco Central</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-6 h-6 text-[var(--color-neon-primary)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M2.166 4.999A11.954 11.954 0 0010 1.944 11.954 11.954 0 0017.834 5c.11.65.166 1.32.166 2.001 0 5.225-3.34 9.67-8 11.317C5.34 16.67 2 12.225 2 7c0-.682.057-1.35.166-2.001zm11.541 3.708a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd"/></svg>
                        <span class="text-sm font-medium">100% Seguro</span>
                    </div>
                    <div class="flex items-center gap-2">
                        <svg class="w-6 h-6 text-[var(--color-neon-primary)]" fill="currentColor" viewBox="0 0 20 20"><path d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"/><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z" clip-rule="evenodd"/></svg>
                        <span class="text-sm font-medium">Zero tarifas</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- Neon Features Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-neon-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Neon Digital</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Banco digital completo.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">Sem complicação.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Purple Card -->
                    <div class="bg-gradient-to-br from-[#7C3AED] to-[#4C1D95] rounded-3xl p-12 aspect-[4/3] relative overflow-hidden flex items-center justify-center shadow-2xl">
                        <!-- Abstract UI Elements -->
                        <div class="relative z-10 w-full max-w-[320px]">
                            <!-- Credit Card -->
                            <div class="bg-white/10 backdrop-blur-xl border border-white/20 rounded-2xl p-6 mb-8 shadow-xl relative overflow-hidden group hover:scale-105 transition-transform duration-500">
                                <div class="absolute top-0 right-0 p-6 opacity-50">
                                    <svg class="w-12 h-8 text-white" viewBox="0 0 48 32" fill="currentColor">
                                        <path d="M32 0H16C7.163 0 0 7.163 0 16s7.163 16 16 16h16c8.837 0 16-7.163 16-16S40.837 0 32 0z" fill-opacity="0.5"/>
                                        <circle cx="16" cy="16" r="16" fill-opacity="0.5"/>
                                    </svg>
                                </div>
                                <div class="w-12 h-8 bg-[#D4AF37] rounded-md mb-8 relative z-10"></div>
                                <div class="space-y-1 relative z-10">
                                    <div class="text-white/60 text-[10px] uppercase tracking-wider font-medium">Titular</div>
                                    <div class="text-white font-mono text-lg tracking-widest">MARIA SILVA</div>
                                </div>
                                <div class="absolute bottom-6 right-6 text-white font-bold italic text-2xl">VISA</div>
                            </div>
                            
                            <!-- Floating Pills -->
                            <div class="relative">
                                <div class="absolute -left-4 top-0 bg-white text-black px-5 py-2.5 rounded-full text-sm font-semibold shadow-lg flex items-center gap-2 transform -rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-green-100 flex items-center justify-center text-green-600">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"/><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Cashback
                                </div>
                                <div class="absolute -right-4 top-12 bg-white/10 backdrop-blur-md text-white px-5 py-2.5 rounded-full text-sm font-semibold border border-white/20 flex items-center gap-2 transform rotate-2">
                                    <div class="w-5 h-5 rounded-full bg-purple-500/30 flex items-center justify-center text-purple-200">
                                        <svg class="w-3 h-3" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M4 4a2 2 0 00-2 2v4a2 2 0 002 2V6h10a2 2 0 00-2-2H4zm2 6a2 2 0 012-2h8a2 2 0 012 2v4a2 2 0 01-2 2H8a2 2 0 01-2-2v-4zm6 4a2 2 0 100-4 2 2 0 000 4z" clip-rule="evenodd"/></svg>
                                    </div>
                                    Sem anuidade
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Crédito aprovado na hora.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            Com o Viracrédito, você transforma suas economias em CDB em limite de crédito aprovado. Sem burocracia, sem análise demorada. Seu dinheiro trabalhando por você.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">Produtos Neon</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Tudo que você precisa para dominar seu dinheiro.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Simples assim.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        Conhecer todos os produtos
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-neon-primary)]"></span>
                                Viracrédito
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">CDB Neon</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Cartão Cashback</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Pix Neon</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Conta Digital</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Seguros</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Viracrédito" 
                            description="Transforme suas economias em crédito. Converta seu investimento em CDB diretamente em limite de crédito aprovado, sem burocracia e com aprovação garantida."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="CDB Neon" 
                            description="Renda mais que a poupança. Invista a partir de R$ 1 e ganhe até 113% do CDI com resgate imediato, garantido pelo FGC até R$ 250 mil."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Cartão com Cashback" 
                            description="Ganhe em todas as compras. Cartão de crédito sem anuidade com cashback em todas as transações acima de R$ 1. Seu dinheiro de volta automaticamente."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Pix Neon" 
                            description="Pague com a câmera. Use a Lente Neon para pagar via Pix sem digitar nada, ou faça Pix no crédito parcelando transferências de R$ 10 a R$ 500."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="Conta Digital" 
                            description="Zero tarifas, sempre. Conta digital 100% gratuita com transferências ilimitadas para qualquer banco, pagamento de contas e recarga de celular sem custo."
                            icon="guard"
                            image="guard"
                        />
                         <FeatureRow 
                            title="Seguros" 
                            description="Proteção completa. Seguro para seu cartão, celular e muito mais. Fatura Protegida e outras coberturas para sua tranquilidade."
                            icon="lab"
                            image="lab"
                        />
                    </div>
                </div>

                <!-- Business Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-blue-100 to-purple-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-blue-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Soluções completas para MEI e empresas — com o MEI Fácil integrado ao app Neon.
                    </h2>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        Conhecer Conta PJ
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Social Proof Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Mais de 30 milhões de brasileiros já confiam na Neon.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Main Card (Large) -->
                        <div class="md:col-span-2 bg-gradient-to-br from-purple-600 to-blue-600 rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-between">
                            <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-3 mb-8">
                                    <svg width="32" height="32" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <rect x="4" y="4" width="11" height="11" rx="2" fill="white" />
                                        <rect x="9" y="9.5" width="10" height="10" rx="2" fill="white" fill-opacity="0.24" />
                                    </svg>
                                    <span class="text-white font-bold text-2xl">Neon</span>
                                </div>
                                <div class="space-y-4 text-white">
                                    <div class="flex items-center gap-3">
                                        <div class="w-12 h-12 rounded-full bg-white/20 backdrop-blur-sm flex items-center justify-center">
                                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20"><path d="M9 6a3 3 0 11-6 0 3 3 0 016 0zM17 6a3 3 0 11-6 0 3 3 0 016 0zM12.93 17c.046-.327.07-.66.07-1a6.97 6.97 0 00-1.5-4.33A5 5 0 0119 16v1h-6.07zM6 11a5 5 0 015 5v1H1v-1a5 5 0 015-5z"/></svg>
                                        </div>
                                        <div>
                                            <div class="text-3xl font-bold">30M+</div>
                                            <div class="text-sm opacity-80">clientes ativos</div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="relative z-10">
                                <h3 class="text-2xl font-bold text-white mb-4">
                                    Reconhecida como World Best Banks em 2020
                                </h3>
                                <p class="text-white/80 text-sm">Autorizada pelo Banco Central do Brasil como Instituição de Pagamento</p>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Card 2 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-center items-center text-center">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-4xl font-bold text-white mb-2">R$ 1,6B</div>
                                    <div class="text-sm text-gray-400">Investimento recebido</div>
                                </div>
                            </div>
                            <!-- Card 3 -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-center items-center text-center">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <div class="text-4xl font-bold text-white mb-2">2016</div>
                                    <div class="text-sm text-gray-400">Primeiro banco digital do Brasil</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-purple-500/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-blue-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Abra sua conta em minutos. <span class="text-[var(--color-neon-primary)]">100% pelo app.</span>
                        </h2>
                        <p class="text-gray-400 mb-10">
                            Simples, rápido e seguro. Baixe o app Neon, confirme seus dados e pronto. Sua conta digital completa em minutos, sem burocracia.
                        </p>
                        <div class="flex gap-4 justify-center">
                            <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-6 py-3 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M18.71 19.5c-.83 1.24-1.71 2.45-3.05 2.47-1.34.03-1.77-.79-3.29-.79-1.53 0-2 .77-3.27.82-1.31.05-2.3-1.32-3.14-2.53C4.25 17 2.94 12.45 4.7 9.39c.87-1.52 2.43-2.48 4.12-2.51 1.28-.02 2.5.87 3.29.87.78 0 2.26-1.07 3.81-.91.65.03 2.47.26 3.64 1.98-.09.06-2.17 1.28-2.15 3.81.03 3.02 2.65 4.03 2.68 4.04-.03.07-.42 1.44-1.38 2.83M13 3.5c.73-.83 1.94-1.46 2.94-1.5.13 1.17-.34 2.35-1.04 3.19-.69.85-1.83 1.51-2.95 1.42-.15-1.15.41-2.35 1.05-3.11z"/></svg>
                                App Store
                            </div>
                            <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-md border border-white/10 rounded-full px-6 py-3 text-white text-sm hover:bg-white/20 transition-colors cursor-pointer">
                                <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M3,20.5V3.5C3,2.91 3.34,2.39 3.84,2.15L13.69,12L3.84,21.85C3.34,21.6 3,21.09 3,20.5M16.81,15.12L6.05,21.34L14.54,12.85L16.81,15.12M20.16,10.81C20.5,11.08 20.75,11.5 20.75,12C20.75,12.5 20.53,12.9 20.18,13.18L17.89,14.5L15.39,12L17.89,9.5L20.16,10.81M6.05,2.66L16.81,8.88L14.54,11.15L6.05,2.66Z"/></svg>
                                Google Play
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Features Grid -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Pix. Apple Pay. Transferências.<br>
                        <span class="text-gray-400">Tudo que você precisa,<br>integrado em um só lugar.</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        Ver todos os recursos
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Pix', 'Apple Pay', 'Visa', 'Mastercard', 'FGC', 'Banco Central', 'TED', 'Boleto'] as feature}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center opacity-60 hover:opacity-100 transition-all duration-300">
                            <span class="font-bold text-xl uppercase tracking-wider">{feature}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Aprenda mais sobre educação financeira.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-purple-200 to-blue-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute inset-0 flex items-center justify-center">
                                    <div class="grid grid-cols-6 gap-4 opacity-50">
                                        {#each Array(24) as _}
                                            <svg class="w-6 h-6 text-purple-600 transform -rotate-45" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                                        {/each}
                                    </div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Investimentos</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-purple-600 transition-colors">Como o CDB pode render mais que a poupança</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="flex gap-4">
                                    <div class="w-16 h-16 rounded-full bg-green-400 blur-xl opacity-80"></div>
                                    <div class="w-20 h-20 rounded-full bg-purple-400 blur-xl opacity-80"></div>
                                    <div class="w-12 h-12 rounded-full bg-blue-400 blur-xl opacity-80"></div>
                                </div>
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Crédito</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-purple-600 transition-colors">Viracrédito: transforme suas economias em limite aprovado</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

