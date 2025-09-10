import { useState, useEffect, createContext, useContext } from "react";
import { Languages, ArrowRight, Calculator, Shield, Handshake, Building2, FileCheck2, UserRoundCheck, Banknote, Mail, Phone, Check, Scale, CreditCard } from "lucide-react";

/**
 * Kettera Website — Draft v2 (React + Tailwind, Bilingual)
 * Clean, minimal, professional. Primary palette: white + brand blue from your logo.
 *
 * HOW TO BRAND:
 * 1) Set exact colors from your logo below (BRAND_BLUE, BRAND_NAVY)
 * 2) Set LOGO_URL to your SVG/PNG in the Asset Manager of this canvas (drag-drop).
 * 3) Replace trust-bar placeholders with official logos once cleared.
 */

// ---- Brand tokens (replace with final hex from your logo) ----
const BRAND_BLUE = "#0A5BD3";   // Primary action/links
const BRAND_NAVY = "#0B1D3A";   // Headlines/text accents
const BRAND_BG = "#ffffff";     // Background (keep clean)
const LOGO_URL = "";            // e.g. "/assets/kettera-logo.svg"

// ---- i18n setup ----
const I18n = createContext({ lang: "es", t: (k) => k, setLang: () => {} });
const useI18n = () => useContext(I18n);

const copy = {
  es: {
    nav: { problem: "El problema", approach: "Nuestro enfoque", products: "Productos", how: "Cómo funciona", trust: "Confianza", costs: "Costos", apply: "Solicita" },
    hero: {
      h1: "Sin esperas. Sin deudas. Solo liquidez inmediata.",
      subA: "Cotización en 72 horas. Financiamiento en 24 horas una vez aprobado.",
      subC: "Supervisados por CNBV, miembros de ASOFOM, con procesos y cuentas seguras.",
      cta1: "Solicita tu línea",
      cta2: "Calcula tu costo"
    },
    problem: {
      h2: "El problema",
      p: "Tus clientes pagan a 60, 90 o hasta 120 días. Mientras tanto, tu negocio necesita liquidez para operar y crecer. Los bancos tardan meses y piden garantías; los fintechs genéricos ofrecen líneas pequeñas y poco confiables."
    },
    approach: {
      h2: "Nuestro enfoque",
      p1: "No damos líneas genéricas basadas en % de ventas. Analizamos cada relación vendedor–comprador usando datos del SAT (CIEC) y su comportamiento de pago.",
      p2: "Establecemos límites específicos por deudor. Resultado: líneas más grandes, más estables y confiables que los modelos genéricos.",
      bullets: [
        "Venta verdadera; enfoque sin recurso (donde aplique)",
        "Disciplina de cobranza con cuentas de control por deudor e instrucciones notariales",
        "Autoliquidable: cuando pagan las facturas, tu saldo baja automáticamente"
      ]
    },
    how: {
      h2: "Cómo funciona",
      steps: [
        { t: "Conecta y comparte", d: "RFC y facturas vía SAT (CIEC) + información básica." },
        { t: "Analizamos y dimensionamos", d: "Límites por deudor según comportamiento real." },
        { t: "Onboarding y notificaciones", d: "KYC/AML, contratos digitales, cuentas STP, aviso por notario." },
        { t: "Fondeo continuo", d: "Post-onboarding, facturas elegibles típicamente en 24h." }
      ],
      foot: "*Tiempos sujetos a documentación, límites aprobados y horarios operativos."
    },
    products: {
      h2: "Productos",
      receivables: { title: "Factoraje (CxC)", bullets: ["Anticipo hasta 80% (reserva típica 20%)", "Venta verdadera; enfoque sin recurso", "Fuera de balance; autoliquidable"] },
      payables: { title: "Confirming (CxP)", bullets: ["Pago anticipado a proveedores", "Conserva descuentos", "Estabiliza tu cadena de suministro"] },
      programs: { title: "Soluciones programáticas", bullets: ["Programas anclados a grandes compradores", "Estructuradas y aseguradas", "A la medida"] }
    },
    trust: {
      h2: "Por qué confiar en Kettera",
      bullets: [
        "Marco regulatorio CNBV/SHCP; sujetos a CONDUSEF",
        "Reportamos a sociedades de información crediticia (p.ej. Buró de Crédito)",
        "Miembros de ASOFOM (la asociación más grande de SOFOMes en LatAm)",
        "KYC/AML, RUG, cuentas de control por deudor e instrucciones notariales",
        "Priorizamos cuentas por cobrar aseguradas"
      ]
    },
    costs: {
      h2: "Costos & Calculadora",
      bullets: [
        "Comisión: 0.8% – 1.5% por factura financiada",
        "Tasa: TIIE + 9% – 13% anual (costo diario)",
        "Sin comisión de apertura ni de línea — pagas lo que usas"
      ],
      calc: { invoice: "Monto de factura (MXN)", days: "Días al pago", advance: "Anticipo", rate: "Tasa sobre TIIE", results: { title: "Resultados", gross: "Anticipo bruto", fee: "Costo estimado", net: "Desembolso neto", note: "*Estimación no vinculante; depende de límites, documentación y seguros." } },
      cta: "Solicita tu línea"
    },
    apply: {
      h2: "Solicita",
      steps: [
        "Envíanos tu CIEC → cotización indicativa en 72h",
        "Onboarding digital y validación de deudores",
        "Aprobación de comité y firma digital",
        "Cuentas STP y notificación a deudores → listo para fondear"
      ],
      form: { name: "Nombre completo", company: "Empresa", email: "Email", phone: "Teléfono", msg: "Necesidad (breve)", submit: "Solicitar contacto" }
    },
    footer: { rights: (y) => `© ${y} Grupo Kettera. Todos los derechos reservados.` }
  },
  en: {
    nav: { problem: "Problem", approach: "Approach", products: "Products", how: "How it works", trust: "Trust", costs: "Costs", apply: "Apply" },
    hero: {
      h1: "No waiting. No debt. Just immediate liquidity.",
      subA: "Indicative quote in 72 hours. Funding in 24 hours once approved.",
      subC: "Supervised by CNBV, member of ASOFOM, with secure processes and accounts.",
      cta1: "Apply now",
      cta2: "Estimate costs"
    },
    problem: {
      h2: "The problem",
      p: "Your buyers pay in 60, 90 or even 120 days. Meanwhile, you need liquidity to operate and grow. Banks take months and demand collateral; generic fintechs offer small, unreliable lines."
    },
    approach: {
      h2: "Our approach",
      p1: "We don’t do blunt % of sales lines. We analyze each seller→buyer relationship using SAT (CIEC) data and real payment behavior.",
      p2: "We set specific limits per obligor. Result: larger, steadier, more reliable facilities than generic models.",
      bullets: [
        "True sale; non‑recourse focus (where applicable)",
        "Collections discipline with per‑obligor control accounts and notary instructions",
        "Self‑liquidating: when invoices pay, your balance drops automatically"
      ]
    },
    how: {
      h2: "How it works",
      steps: [
        { t: "Connect & share", d: "RFC + invoices via SAT (CIEC) and basic info." },
        { t: "Analyze & size", d: "Per‑obligor limits based on real behavior." },
        { t: "Onboard & notify", d: "KYC/AML, digital contracts, STP accounts, notary notices." },
        { t: "Ongoing funding", d: "Post‑onboarding, eligible invoices typically in 24h." }
      ],
      foot: "*Timing subject to documentation, approved limits and operating hours."
    },
    products: {
      h2: "Products",
      receivables: { title: "Receivables (Factoring)", bullets: ["Advance up to 80% (typical 20% reserve)", "True sale; non‑recourse focus", "Off balance sheet; self‑liquidating"] },
      payables: { title: "Confirming (Payables)", bullets: ["Early pay to suppliers", "Keep discounts", "Stabilize your supply chain"] },
      programs: { title: "Programmatic solutions", bullets: ["Facilities anchored to large buyers", "Structured and insured", "Tailored"] }
    },
    trust: {
      h2: "Why trust Kettera",
      bullets: [
        "CNBV/SHCP regulatory ecosystem; submit to CONDUSEF",
        "We report to credit information societies (e.g., Buró de Crédito)",
        "Member of ASOFOM (largest NBFI association in LatAm)",
        "KYC/AML, RUG, per‑obligor control accounts and notary notices",
        "We prioritize insured receivables"
      ]
    },
    costs: {
      h2: "Costs & Calculator",
      bullets: [
        "Commission: 0.8% – 1.5% per financed invoice",
        "Rate: TIIE + 9% – 13% p.a. (daily cost)",
        "No opening or line fees — you pay for what you use"
      ],
      calc: { invoice: "Invoice amount (MXN)", days: "Days to payment", advance: "Advance", rate: "Spread over TIIE", results: { title: "Results", gross: "Gross advance", fee: "Estimated cost", net: "Net disbursement", note: "*Non‑binding estimate; depends on limits, documentation and insurance." } },
      cta: "Apply now"
    },
    apply: {
      h2: "Apply",
      steps: [
        "Send us your CIEC → indicative quote in 72h",
        "Digital onboarding and obligor validation",
        "Credit committee approval & digital signing",
        "STP accounts and obligor notices → ready to fund"
      ],
      form: { name: "Full name", company: "Company", email: "Email", phone: "Phone", msg: "Need (brief)", submit: "Request contact" }
    },
    footer: { rights: (y) => `© ${y} Grupo Kettera. All rights reserved.` }
  }
};

export default function KetteraSite(){
  const [lang, setLang] = useState("es");
  useEffect(()=>{ const s = localStorage.getItem("kettera_lang"); if(s) setLang(s); },[]);
  useEffect(()=>{ localStorage.setItem("kettera_lang", lang); },[lang]);
  const t = (key) => key.split(".").reduce((o,k)=> (o && o[k] !== undefined) ? o[k] : key, copy[lang]);
  return (
    <I18n.Provider value={{ lang, setLang, t }}>
      <Style />
      <div className="min-h-screen" style={{background:BRAND_BG, color:"#0f172a"}}>
        <Topbar />
        <Hero />
        <Section id="problem"><Problem /></Section>
        <MetricsBar />
        <Section id="approach"><Approach /></Section>
        <Section id="how"><HowItWorks /></Section>
        <Section id="products"><Products /></Section>
        <Section id="trust"><Trust /></Section>
        <Section id="costs"><CostsAndCalc /></Section>
        <Section id="apply"><Apply /></Section>
        <Footer />
        <SmokeTests />
      </div>
    </I18n.Provider>
  );
}

function Style(){
  return (
    <style>{`
      :root { --blue: ${BRAND_BLUE}; --navy: ${BRAND_NAVY}; }
      html { scroll-behavior: smooth; }
      section[id]{ scroll-margin-top: 84px; }
      .btn { padding: .7rem 1rem; border-radius: 12px; font-weight: 600; }
      .btn-primary { background: var(--blue); color: #fff; }
      .btn-primary:hover { filter: brightness(.95); }
      .btn-ghost { background: transparent; border: 1px solid #e5e7eb; }
      .card { background: #fff; border: 1px solid #eef0f3; border-radius: 16px; box-shadow: 0 2px 6px rgba(16,24,40,.04); }
      .input { width: 100%; padding: .6rem .8rem; border: 1px solid #e5e7eb; border-radius: 12px; }
      .input:focus { outline: none; box-shadow: 0 0 0 2px rgba(10,91,211,.2); border-color: var(--blue); }
      .title { color: var(--navy); }
    `}</style>
  );
}

function Section({ id, children }){
  return (
    <section id={id} className="py-14 md:py-16">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">{children}</div>
    </section>
  );
}

function Topbar(){
  const { lang, setLang, t } = useI18n();
  const NavLink = ({to, children}) => <a href={`#${to}`} className="hover:text-gray-700">{children}</a>;
  return (
    <header className="sticky top-0 z-50 bg-white/90 backdrop-blur border-b border-gray-100">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between">
        <div className="flex items-center gap-3">
          {LOGO_URL ? <img src={LOGO_URL} alt="Kettera" className="h-8 w-auto object-contain"/> : <div className="h-6 w-28 bg-gray-200 rounded"/>}
        </div>
        <nav className="hidden md:flex items-center gap-7 text-sm">
          <NavLink to="problem">{t("nav.problem")}</NavLink>
          <NavLink to="approach">{t("nav.approach")}</NavLink>
          <NavLink to="products">{t("nav.products")}</NavLink>
          <NavLink to="how">{t("nav.how")}</NavLink>
          <NavLink to="trust">{t("nav.trust")}</NavLink>
          <NavLink to="costs">{t("nav.costs")}</NavLink>
        </nav>
        <div className="flex items-center gap-3">
          <button onClick={()=> setLang(lang === "es" ? "en" : "es")} className="text-sm px-3 py-2 rounded-lg hover:bg-gray-100"><Languages className="inline h-4 w-4 mr-1"/>{lang.toUpperCase()} / {lang === "es" ? "EN" : "ES"}</button>
          <a href="#apply" className="btn btn-primary inline-flex items-center gap-2">{t("hero.cta1")}<ArrowRight className="h-4 w-4"/></a>
        </div>
      </div>
    </header>
  );
}

function Hero(){
  const { t } = useI18n();
  return (
    <section className="py-16 md:py-20">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h1 className="text-4xl md:text-5xl font-bold title">{t("hero.h1")}</h1>
          <p className="mt-5 text-lg text-gray-700 max-w-xl">{t("hero.subA")}</p>
          <p className="mt-1 text-gray-600 max-w-xl">{t("hero.subC")}</p>
          <div className="mt-7 flex flex-wrap gap-3">
            <a href="#apply" className="btn btn-primary inline-flex items-center gap-2">{t("hero.cta1")}<ArrowRight className="h-4 w-4"/></a>
            <a href="#costs" className="btn btn-ghost inline-flex items-center gap-2">{t("hero.cta2")}<Calculator className="h-4 w-4"/></a>
          </div>
        </div>
        <div className="card p-6">
          <MiniApply />
        </div>
      </div>
    </section>
  );
}

function MetricsBar(){
  const data = [
    { k: "Clientes establecidos", v: "MX" },
    { k: "Límites por deudor", v: "Sí" },
    { k: "Focus sin recurso", v: "Sí" },
    { k: "Cuentas de control", v: "Por deudor" }
  ];
  return (
    <div className="py-5 border-y border-gray-100 bg-white">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-2 md:grid-cols-4 gap-4 text-sm">
        {data.map((d,i)=> (
          <div key={i} className="flex flex-col md:flex-row md:items-baseline gap-1">
            <span className="text-gray-600">{d.k}</span>
            <span className="font-semibold" style={{color:BRAND_NAVY}}>{d.v}</span>
          </div>
        ))}
      </div>
    </div>
  );
}

function Problem(){
  const { t } = useI18n();
  return (
    <div className="grid md:grid-cols-3 gap-6 items-start">
      <div className="md:col-span-2">
        <h2 className="text-2xl md:text-3xl font-semibold title">{t("problem.h2")}</h2>
        <p className="mt-3 text-gray-700">{t("problem.p")}</p>
      </div>
      <div className="card p-6">
        <div className="font-medium title mb-2">Fintech speed. Bank discipline.</div>
        <ul className="text-sm text-gray-600 space-y-2">
          <li className="flex gap-2"><Shield className="h-4 w-4"/>Bank‑grade underwriting</li>
          <li className="flex gap-2"><Handshake className="h-4 w-4"/>Buyer‑specific limits</li>
          <li className="flex gap-2"><CreditCard className="h-4 w-4"/>Self‑liquidating facilities</li>
        </ul>
      </div>
    </div>
  );
}

function Approach(){
  const { t } = useI18n();
  const bullets = t("approach.bullets");
  return (
    <div className="grid md:grid-cols-2 gap-8 items-start">
      <div>
        <h2 className="text-2xl md:text-3xl font-semibold title">{t("approach.h2")}</h2>
        <p className="mt-3 text-gray-700">{t("approach.p1")}</p>
        <p className="mt-2 text-gray-700">{t("approach.p2")}</p>
      </div>
      <div className="grid gap-3">
        {bullets.map((b,i)=> (
          <div key={i} className="card p-4 text-sm flex items-start gap-2"><Check className="h-4 w-4"/>{b}</div>
        ))}
      </div>
    </div>
  );
}

function HowItWorks(){
  const { t } = useI18n();
  const steps = t("how.steps");
  const icons = [<FileCheck2 className="h-5 w-5"/>, <UserRoundCheck className="h-5 w-5"/>, <Building2 className="h-5 w-5"/>, <Banknote className="h-5 w-5"/>];
  return (
    <div>
      <h2 className="text-2xl md:text-3xl font-semibold title mb-6">{t("how.h2")}</h2>
      <div className="grid md:grid-cols-4 gap-6">
        {steps.map((s,i)=> (
          <div key={i} className="card p-6">
            <div className="h-10 w-10 rounded-xl grid place-items-center" style={{background:BRAND_BLUE, color:"#fff"}}>{icons[i]}</div>
            <div className="font-semibold mt-3 title">{s.t}</div>
            <div className="text-sm text-gray-600">{s.d}</div>
          </div>
        ))}
      </div>
      <div className="text-xs text-gray-500 mt-3">{t("how.foot")}</div>
    </div>
  );
}

function Products(){
  const { t } = useI18n();
  const cards = [
    { title: t("products.receivables.title"), bullets: t("products.receivables.bullets"), icon:<Banknote className="h-5 w-5"/> },
    { title: t("products.payables.title"), bullets: t("products.payables.bullets"), icon:<Handshake className="h-5 w-5"/> },
    { title: t("products.programs.title"), bullets: t("products.programs.bullets"), icon:<Building2 className="h-5 w-5"/> },
  ];
  return (
    <div>
      <h2 className="text-2xl md:text-3xl font-semibold title mb-6">{t("products.h2")}</h2>
      <div className="grid md:grid-cols-3 gap-6">
        {cards.map((c,i)=> (
          <div key={i} className="card overflow-hidden">
            <div className="h-40 w-full" style={{background:"linear-gradient(135deg, rgba(10,91,211,.10), rgba(11,29,58,.06))"}} />
            <div className="p-6">
              <div className="inline-flex items-center gap-2 font-semibold mb-2 title">{c.icon}{c.title}</div>
              <ul className="text-sm text-gray-600 space-y-2">{c.bullets.map((b,j)=> <li key={j} className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5"/>{b}</li>)}</ul>
            </div>
          </div>
        ))}
      </div>
    </div>
  );
}

function Trust(){
  const { t } = useI18n();
  const bullets = t("trust.bullets");
  return (
    <div className="grid md:grid-cols-2 gap-8 items-start">
      <div>
        <h2 className="text-2xl md:text-3xl font-semibold title">{t("trust.h2")}</h2>
        <div className="grid gap-3 mt-3">
          {bullets.map((b,i)=> <div key={i} className="card p-4 text-sm flex items-start gap-2"><Scale className="h-4 w-4"/>{b}</div>)}
        </div>
      </div>
      <div className="card p-6">
        <div className="text-sm text-gray-600 mb-2">Trust bar (logos):</div>
        <div className="grid grid-cols-2 md:grid-cols-4 gap-4 items-center">
          {['CNBV','CONDUSEF','Buró de Crédito','ASOFOM'].map((k)=> (
            <div key={k} className="h-10 bg-gray-100 rounded grid place-items-center text-xs text-gray-600">{k}</div>
          ))}
        </div>
        <div className="text-xs text-gray-500 mt-3">(Replace with official logos once cleared.)</div>
      </div>
    </div>
  );
}

function CostsAndCalc(){
  const { t } = useI18n();
  const [invoice, setInvoice] = useState(500000);
  const [days, setDays] = useState(45);
  const [advance, setAdvance] = useState(0.8);    // 80%
  const [spread, setSpread] = useState(0.11);     // 11% p.a. over TIIE (illustrative)
  const advanceAmt = Math.round(invoice * advance);
  const dailyRate = (spread) / 360;               // p.a. to daily (approx)
  const fee = Math.round(advanceAmt * dailyRate * days);
  const net = Math.max(advanceAmt - fee, 0);

  const bullets = t("costs.bullets");

  return (
    <div className="grid md:grid-cols-2 gap-8 items-start">
      <div>
        <h2 className="text-2xl md:text-3xl font-semibold title">{t("costs.h2")}</h2>
        <ul className="mt-3 text-sm text-gray-700 space-y-2">{bullets.map((b,i)=> <li key={i} className="flex items-start gap-2"><Check className="h-4 w-4 mt-0.5"/>{b}</li>)}</ul>
        <a href="#apply" className="mt-4 inline-flex btn btn-primary items-center gap-2">{t("costs.cta")}<ArrowRight className="h-4 w-4"/></a>
      </div>
      <div className="card p-6">
        <div className="flex items-center gap-2 mb-4"><Calculator className="h-5 w-5"/><h3 className="text-xl font-semibold title">{t("costs.h2")}</h3></div>
        <div className="grid md:grid-cols-2 gap-4 text-sm">
          <NumberInput label={t("costs.calc.invoice")} value={invoice} onChange={setInvoice} step={50000} min={100000} />
          <RangeInput label={t("costs.calc.days")} value={days} onChange={setDays} min={15} max={120} step={5} format={(v)=>`${v}`} />
          <RangeInput label={t("costs.calc.advance")} value={advance} onChange={setAdvance} min={0.6} max={0.9} step={0.05} format={(v)=>`${Math.round(v*100)}%`} />
          <RangeInput label={t("costs.calc.rate")} value={spread} onChange={setSpread} min={0.09} max={0.13} step={0.005} format={(v)=>`${(v*100).toFixed(1)}%`} />
          <div className="rounded-xl p-4 md:col-span-2" style={{background:"#f6f8fb"}}>
            <div className="font-medium title">{t("costs.calc.results.title")}</div>
            <div className="mt-2 space-y-1">
              <Row k={t("costs.calc.results.gross")} v={`$${advanceAmt.toLocaleString()}`} />
              <Row k={t("costs.calc.results.fee")} v={`$${fee.toLocaleString()}`} />
              <Row k={t("costs.calc.results.net")} v={`$${net.toLocaleString()}`} />
            </div>
            <div className="text-xs text-gray-500 mt-2">{t("costs.calc.results.note")}</div>
          </div>
        </div>
      </div>
    </div>
  );
}

function Apply(){
  const { t } = useI18n();
  const steps = t("apply.steps");
  return (
    <div className="grid md:grid-cols-2 gap-8 items-start">
      <div>
        <h2 className="text-2xl md:text-3xl font-semibold title">{t("apply.h2")}</h2>
        <ol className="mt-3 space-y-2 text-sm text-gray-700 list-decimal list-inside">
          {steps.map((s,i)=> <li key={i}>{s}</li>)}
        </ol>
      </div>
      <form className="card p-6 space-y-3">
        <input className="input" placeholder={t("apply.form.name")} />
        <input className="input" placeholder={t("apply.form.company")} />
        <input className="input" placeholder={t("apply.form.email")} type="email" />
        <input className="input" placeholder={t("apply.form.phone")} />
        <textarea className="input h-24" placeholder={t("apply.form.msg")} />
        <button type="button" className="w-full btn btn-primary">{t("apply.form.submit")}</button>
      </form>
    </div>
  );
}

function MiniApply(){
  const { t } = useI18n();
  return (
    <form className="space-y-3">
      <div className="font-medium title mb-1">Quick apply</div>
      <input className="input" placeholder={t("apply.form.company")} />
      <input className="input" placeholder="RFC" />
      <input className="input" placeholder={t("apply.form.email")} type="email" />
      <button type="button" className="w-full btn btn-primary">{t("apply.form.submit")}</button>
      <p className="text-xs text-gray-500">Al enviar aceptas nuestro Aviso de Privacidad / By submitting you accept our Privacy Notice.</p>
    </form>
  );
}

function NumberInput({ label, value, onChange, step=10000, min=0 }){
  return (
    <label className="block">
      <span className="text-gray-700">{label}</span>
      <input type="number" value={value} min={min} step={step} onChange={(e)=> onChange(parseInt(e.target.value||"0",10))} className="input mt-1" />
    </label>
  );
}

function RangeInput({ label, value, onChange, min, max, step, format }){
  return (
    <label className="block">
      <span className="text-gray-700">{label}: <span className="font-medium">{format(value)}</span></span>
      <input type="range" min={min} max={max} step={step} value={value} onChange={(e)=> onChange(parseFloat(e.target.value))} className="w-full" />
    </label>
  );
}

function Row({ k, v }){ return <div className="flex items-center justify-between"><span className="text-gray-600">{k}</span><span className="font-semibold">{v}</span></div>; }

function Footer(){
  const { t } = useI18n();
  return (
    <footer className="mt-12" style={{background:BRAND_NAVY, color:"#c9d3ff"}}>
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 grid md:grid-cols-4 gap-8">
        <div>
          {LOGO_URL ? <img src={LOGO_URL} alt="Kettera" className="h-7 w-auto object-contain"/> : <div className="h-6 w-28 bg-white/20 rounded"/>}
          <p className="text-sm mt-2">Receivables finance and supply‑chain solutions.</p>
        </div>
        <div>
          <div className="text-white font-medium mb-2">Site</div>
          <ul className="space-y-2 text-sm">
            <li><a href="#products" className="hover:underline text-inherit">Products</a></li>
            <li><a href="#how" className="hover:underline text-inherit">How it works</a></li>
            <li><a href="#trust" className="hover:underline text-inherit">Trust</a></li>
            <li><a href="#costs" className="hover:underline text-inherit">Costs</a></li>
          </ul>
        </div>
        <div>
          <div className="text-white font-medium mb-2">Legal</div>
          <ul className="space-y-2 text-sm">
            <li><a className="text-inherit">Privacy</a></li>
            <li><a className="text-inherit">Terms</a></li>
            <li><a className="text-inherit">AML/PLD</a></li>
          </ul>
        </div>
        <div className="text-sm flex items-end">{t("footer.rights")(new Date().getFullYear())}</div>
      </div>
    </footer>
  );
}

// ---- Smoke tests (runtime checks) ----
function SmokeTests(){
  useEffect(() => {
    try {
      console.assert(/^#/.test(BRAND_BLUE) && /^#/.test(BRAND_NAVY), "Brand colors should be hex");
      console.assert(copy.es.hero.h1 && copy.en.hero.h1, "Bilingual hero present");
      console.assert(typeof LOGO_URL === "string", "LOGO_URL should be set to your asset path");
      // Calculator sample
      const invoice = 500000; const adv=0.8; const spread=0.11; const days=45;
      const advanceAmt = Math.round(invoice*adv);
      const fee = Math.round(advanceAmt*(spread/360)*days);
      const net = Math.max(advanceAmt-fee,0);
      console.assert(advanceAmt>0 && fee>=0 && net>=0, "Calculator outputs should be numbers");
      console.log("Smoke tests passed");
    } catch (e) {
      console.error("Smoke tests failed", e);
    }
  }, []);
  return null;
}
