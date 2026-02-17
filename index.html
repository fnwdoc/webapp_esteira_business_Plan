<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plano de Negócios FNW Assessoria Esteira</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary': '#1e3a8a',
                        'secondary': '#3b82f6',
                        'accent': '#f59e0b',
                        'background': '#f1f5f9',
                    },
                    fontFamily: { sans: ['Inter', 'sans-serif'] }
                }
            }
        }
    </script>
    <style>
        .input-field { @apply p-2 w-full bg-white border border-gray-300 rounded text-sm focus:ring-2 focus:ring-secondary focus:border-secondary outline-none transition-all; }
        input::-webkit-outer-spin-button, input::-webkit-inner-spin-button { -webkit-appearance: none; margin: 0; }
        .col-nome { width: 30%; }
        .col-preco { width: 15%; }
        .col-cap { width: 15%; }
        .col-un { width: 15%; }
        .col-total { width: 25%; }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
</head>
<body class="bg-background min-h-screen p-4 md:p-8 font-sans">

    <div id="notification-bar" class="fixed top-0 left-1/2 transform -translate-x-1/2 mt-4 p-3 rounded-lg shadow-xl text-white font-semibold hidden transition-opacity duration-300 z-50">
        <span id="notification-text"></span>
    </div>

    <div class="max-w-7xl mx-auto">
        <header class="text-center mb-10 p-6 bg-white rounded-xl shadow-lg">
            <h1 class="text-3xl font-extrabold text-primary">FNW Assessoria Esteira</h1>
            <p class="mt-2 text-gray-600 italic">Foco em IA e Mentorias Educacionais</p>
        </header>

        <section class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-10">
            <div class="bg-white p-6 rounded-xl shadow-xl border-b-4 border-secondary transition hover:shadow-2xl">
                <p class="text-sm font-medium text-gray-500 uppercase">Receita Mensal MÁXIMA</p>
                <h2 id="max-revenue" class="mt-1 text-3xl font-bold text-secondary">R$ 0,00</h2>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-xl border-b-4 border-accent transition hover:shadow-2xl">
                <p class="text-sm font-medium text-gray-500 uppercase">Meta de Crescimento/Mês</p>
                <h2 id="monthly-growth-target" class="mt-1 text-3xl font-bold text-accent">R$ 0,00</h2>
            </div>
            <div class="bg-white p-6 rounded-xl shadow-xl border-b-4 border-primary transition hover:shadow-2xl">
                <label class="text-sm font-medium text-gray-500 block uppercase italic">Regra de Divisão Principal (%)</label>
                <div class="mt-1 flex items-center space-x-2">
                    <input type="number" id="assessor-share" value="25.00" step="0.01" oninput="handleAssessorShareChange(this.value)" class="bg-transparent text-3xl font-bold text-primary w-24 outline-none" />
                    <span class="text-3xl font-bold text-primary">%</span>
                </div>
            </div>
        </section>

        <div class="bg-white rounded-xl shadow-xl overflow-hidden">
            <div class="flex bg-gray-50 border-b">
                <button onclick="showSection('portfolio')" class="tab-button px-8 py-4 font-bold text-sm uppercase tracking-wider border-r border-t-4 border-t-transparent" data-section="portfolio">Portfólio (Editar)</button>
                <button onclick="showSection('growth')" class="tab-button px-8 py-4 font-bold text-sm uppercase tracking-wider border-r border-t-4 border-t-transparent" data-section="growth">Projeção & Divisão</button>
            </div>

            <div id="portfolio-section" class="content-section p-6">
                <div class="flex items-center justify-between mb-4">
                    <h3 class="text-xl font-bold text-primary uppercase tracking-tight">Configuração da Esteira de Produtos</h3>
                    
                    <a href="https://fnwdoc.github.io/webapp_esteira_digital/" target="_blank" rel="noopener noreferrer" 
                       class="flex items-center space-x-2 bg-gray-100 text-gray-700 text-xs px-4 py-2 rounded-lg border hover:bg-gray-200 transition shadow-sm font-bold uppercase">
                        <span>Abrir Esteira Digital</span>
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4m-4-7a3 3 0 00-3-3H9a3 3 0 00-3 3v8a3 3 0 003 3h8a3 3 0 003-3v-5m-4 0l-5 5"></path>
                        </svg>
                    </a>
                </div>

                <div class="overflow-x-auto border rounded-lg">
                    <table class="min-w-full table-fixed divide-y divide-gray-200">
                        <thead class="bg-gray-100 uppercase text-[10px] font-bold text-gray-600">
                            <tr>
                                <th class="col-nome px-4 py-3 text-left border-r text-xs">Produto/Serviço</th>
                                <th class="col-preco px-4 py-3 text-center border-r text-xs">Preço (R$)</th>
                                <th class="col-cap px-4 py-3 text-center border-r text-xs">Capacidade</th>
                                <th class="col-un px-4 py-3 text-center border-r text-xs">Unidade</th>
                                <th class="col-total px-4 py-3 text-right text-primary text-xs">Receita Bruta (Máx)</th>
                            </tr>
                        </thead>
                        <tbody id="portfolio-table-body" class="bg-white divide-y divide-gray-200"></tbody>
                        <tfoot class="bg-primary/10 border-t-2 border-primary text-primary font-black">
                            <tr>
                                <td colspan="4" class="px-6 py-4 text-right uppercase">Receita Total Mensal Projetada:</td>
                                <td id="total-revenue-footer" class="px-6 py-4 text-xl text-right">R$ 0,00</td>
                            </tr>
                        </tfoot>
                    </table>
                </div>
            </div>

            <div id="growth-section" class="content-section p-6 hidden">
                <div class="mb-8 grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="p-4 bg-yellow-50 rounded-lg border border-yellow-200">
                        <label class="block text-sm font-bold text-gray-700 mb-2 uppercase">Período para Escala (Meses):</label>
                        <div class="flex items-center gap-3">
                            <input type="number" id="growth-period" value="18" oninput="handleGrowthPeriodChange(this.value)" class="w-24 p-2 border rounded font-bold text-center" />
                            <span class="text-sm text-gray-600 font-medium tracking-wide">Meses</span>
                        </div>
                        <div class="mt-4 flex gap-2">
                            <button onclick="saveScenario()" class="bg-green-600 text-white px-3 py-2 rounded text-xs font-bold uppercase shadow hover:bg-green-700">Salvar Plano</button>
                            <button onclick="document.getElementById('file-input').click()" class="bg-gray-600 text-white px-3 py-2 rounded text-xs font-bold uppercase shadow hover:bg-gray-700">Carregar Plano</button>
                            <input type="file" id="file-input" accept=".json" onchange="loadScenario(event)" class="hidden">
                        </div>
                    </div>

                    <div class="p-4 bg-blue-50 rounded-lg border border-blue-200">
                        <h4 class="font-bold text-blue-900 uppercase text-xs mb-3 italic">Detalhes Sessão Especial</h4>
                        <div class="space-y-3">
                            <div class="flex justify-between items-center">
                                <span class="text-sm font-medium">Participantes Previstos:</span>
                                <input type="number" id="special-session-participants" value="10" oninput="handleSpecialSessionChange()" class="w-16 p-1 border rounded text-center font-bold text-blue-800" />
                            </div>
                            <div class="flex justify-between items-center">
                                <span class="text-sm font-medium">Divisão Convidado:</span>
                                <div class="flex items-center gap-1">
                                    <input type="number" id="guest-share-percent" value="25.00" oninput="handleGuestShareChange(this.value)" class="w-16 p-1 border rounded text-center font-bold text-blue-800" />
                                    <span class="font-bold text-blue-800">%</span>
                                </div>
                            </div>
                        </div>
                        <div id="special-session-details" class="mt-4 p-2 bg-white rounded border border-blue-100 text-xs text-gray-700 space-y-1"></div>
                    </div>
                </div>

                <div class="overflow-x-auto border rounded-lg mb-8">
                    <table class="min-w-full divide-y divide-gray-200">
                        <thead id="projection-header" class="bg-primary text-white text-[10px] uppercase"></thead>
                        <tbody id="dynamic-projection-table-body" class="divide-y divide-gray-100 text-sm"></tbody>
                    </table>
                </div>

                <div class="bg-green-50 p-4 rounded-lg border border-green-200 shadow-inner">
                    <p class="font-bold text-green-800 uppercase text-[10px] mb-3 tracking-widest">Cronograma de Sessões Especiais:</p>
                    <ul id="special-session-months" class="grid grid-cols-2 md:grid-cols-3 gap-3 text-xs text-green-700 font-bold list-none"></ul>
                </div>
            </div>
        </div>
    </div>

    <script>
        let appState = {
            growthPeriodMonths: 18,
            assessorRevenueSharePercent: 25.00,
            guestPaymentSharePercent: 25.00,
            specialParticipants: 10,
            specialMonths: ["Dezembro / 2025", "Março / 2026", "Maio / 2026", "Agosto / 2026", "Outubro / 2026", "Dezembro / 2026"],
            portfolio: [
                { id: 'p1', name: "E-book interativo com IA", price: 90.00, capacity: 900, unit: "vendas" },
                { id: 'p2', name: "Aulas Online", price: 356.00, capacity: 60, unit: "alunos" },
                { id: 'p3', name: "Mentorias em Grupo", price: 762.00, capacity: 40, unit: "participantes" },
                { id: 'p4', name: "Acompanhamento Individual", price: 1400.00, capacity: 72, unit: "clientes" }
            ]
        };

        const formatCurrency = (v) => new Intl.NumberFormat('pt-BR', { style: 'currency', currency: 'BRL' }).format(v);

        function handleInputChange(id, field, value) {
            const item = appState.portfolio.find(p => p.id === id);
            if (item) {
                if (field === 'price' || field === 'capacity') {
                    item[field] = parseFloat(value) || 0;
                } else {
                    item[field] = value;
                }
                updateAll();
            }
        }

        function handleAssessorShareChange(v) {
            const val = parseFloat(v) || 0;
            appState.assessorRevenueSharePercent = val;
            appState.guestPaymentSharePercent = val;
            document.getElementById('guest-share-percent').value = val.toFixed(2);
            updateAll();
        }

        function handleGuestShareChange(v) {
            const val = parseFloat(v) || 0;
            appState.guestPaymentSharePercent = val;
            appState.assessorRevenueSharePercent = val;
            document.getElementById('assessor-share').value = val.toFixed(2);
            updateAll();
        }

        function handleSpecialSessionChange() {
            appState.specialParticipants = parseInt(document.getElementById('special-session-participants').value) || 0;
            updateAll();
        }

        function handleGrowthPeriodChange(v) {
            appState.growthPeriodMonths = parseInt(v) || 1;
            updateAll();
        }

        function updateAll() {
            let totalMax = 0;
            appState.portfolio.forEach(item => {
                const revenue = item.price * item.capacity;
                totalMax += revenue;
                const cell = document.getElementById(`res-${item.id}`);
                if (cell) cell.textContent = formatCurrency(revenue);
            });

            document.getElementById('max-revenue').textContent = formatCurrency(totalMax);
            document.getElementById('total-revenue-footer').textContent = formatCurrency(totalMax);
            document.getElementById('monthly-growth-target').textContent = formatCurrency(totalMax / appState.growthPeriodMonths);
            
            const groupProduct = appState.portfolio.find(p => p.id === 'p3');
            const sessionGross = groupProduct.price * appState.specialParticipants;
            const sessionGuest = sessionGross * (appState.guestPaymentSharePercent / 100);
            
            document.getElementById('special-session-details').innerHTML = `
                <div class="flex justify-between border-b pb-1"><span>Bruto da Sessão:</span><b>${formatCurrency(sessionGross)}</b></div>
                <div class="flex justify-between border-b py-1"><span>Comissão Convidado (${appState.guestPaymentSharePercent}%):</span><b>${formatCurrency(sessionGuest)}</b></div>
                <div class="flex justify-between pt-1 font-bold text-blue-900"><span>Líquido Assessoria:</span><b>${formatCurrency(sessionGross - sessionGuest)}</b></div>
            `;

            renderDynamicProjectionTable();
        }

        function renderPortfolioTable() {
            const tbody = document.getElementById('portfolio-table-body');
            tbody.innerHTML = '';
            appState.portfolio.forEach((item, idx) => {
                const row = document.createElement('tr');
                row.className = idx % 2 === 0 ? 'bg-white' : 'bg-gray-50/50';
                row.innerHTML = `
                    <td class="px-4 py-3 border-r col-nome font-semibold"><input type="text" value="${item.name}" oninput="handleInputChange('${item.id}', 'name', this.value)" class="input-field text-primary"></td>
                    <td class="px-4 py-3 border-r col-preco"><input type="number" value="${item.price}" oninput="handleInputChange('${item.id}', 'price', this.value)" class="input-field text-center"></td>
                    <td class="px-4 py-3 border-r col-cap"><input type="number" value="${item.capacity}" oninput="handleInputChange('${item.id}', 'capacity', this.value)" class="input-field text-center"></td>
                    <td class="px-4 py-3 border-r col-un"><input type="text" value="${item.unit}" oninput="handleInputChange('${item.id}', 'unit', this.value)" class="input-field text-center italic"></td>
                    <td id="res-${item.id}" class="px-4 py-3 text-right font-bold text-secondary col-total tracking-tight">${formatCurrency(item.price * item.capacity)}</td>
                `;
                tbody.appendChild(row);
            });
        }

        function renderDynamicProjectionTable() {
            const head = document.getElementById('projection-header');
            const body = document.getElementById('dynamic-projection-table-body');
            
            let headHtml = `<tr><th class="px-4 py-3 text-left border-r">Mês</th>`;
            appState.portfolio.forEach(p => headHtml += `<th class="px-4 py-3 text-center border-r">${p.name}</th>`);
            headHtml += `<th class="px-4 py-3 text-right">Faturamento Total</th></tr>`;
            head.innerHTML = headHtml;

            body.innerHTML = '';
            for (let m = 1; m <= appState.growthPeriodMonths; m++) {
                let monthlyTotal = 0;
                let rowHtml = `<td class="px-4 py-2 font-black border-r text-gray-400">#${m}</td>`;
                
                appState.portfolio.forEach(p => {
                    const currentVol = (p.capacity / appState.growthPeriodMonths) * m;
                    monthlyTotal += currentVol * p.price;
                    rowHtml += `<td class="px-4 py-2 text-center border-r text-gray-500 italic">${Math.floor(currentVol)}</td>`;
                });

                rowHtml += `<td class="px-4 py-2 text-right font-bold text-secondary bg-blue-50/30 border-l">${formatCurrency(monthlyTotal)}</td>`;
                const tr = document.createElement('tr');
                tr.className = "hover:bg-amber-50 transition-colors";
                tr.innerHTML = rowHtml;
                body.appendChild(tr);
            }
        }

        function showSection(id) {
            document.querySelectorAll('.content-section').forEach(s => s.classList.add('hidden'));
            document.getElementById(`${id}-section`).classList.remove('hidden');
            document.querySelectorAll('.tab-button').forEach(b => {
                const active = b.dataset.section === id;
                b.classList.toggle('bg-white', active);
                b.classList.toggle('text-primary', active);
                b.classList.toggle('border-t-primary', active);
                b.classList.toggle('text-gray-400', !active);
            });
        }

        function saveScenario() {
            const blob = new Blob([JSON.stringify(appState, null, 2)], { type: 'application/json' });
            const a = document.createElement('a'); a.href = URL.createObjectURL(blob); a.download = `fnw_plano.json`; a.click();
        }

        function loadScenario(event) {
            const reader = new FileReader();
            reader.onload = (e) => {
                appState = JSON.parse(e.target.result);
                document.getElementById('growth-period').value = appState.growthPeriodMonths;
                document.getElementById('assessor-share').value = appState.assessorRevenueSharePercent.toFixed(2);
                document.getElementById('guest-share-percent').value = appState.guestPaymentSharePercent.toFixed(2);
                document.getElementById('special-session-participants').value = appState.specialParticipants;
                renderPortfolioTable();
                updateAll();
            };
            reader.readAsText(event.target.files[0]);
        }

        document.addEventListener('DOMContentLoaded', () => {
            const list = document.getElementById('special-session-months');
            appState.specialMonths.forEach(m => {
                list.innerHTML += `<li class="flex items-center space-x-2"><span class="w-2 h-2 bg-green-500 rounded-full"></span><span>${m}</span></li>`;
            });
            renderPortfolioTable();
            updateAll();
            showSection('portfolio');
        });
    </script>
</body>
</html>
