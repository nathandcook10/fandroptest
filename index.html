import { useState } from "react";

// NOTE: Replace `/fandrop-logo.png` with your actual logo path or URL.
// If you deploy to Vercel/Netlify, put the file in /public and keep the same path.
export default function FandropLanding() {
  const [email, setEmail] = useState("");
  const [status, setStatus] = useState<"idle" | "loading" | "success" | "error">("idle");
  const [error, setError] = useState<string>("");

  const onSubmit = async (e: React.FormEvent) => {
    e.preventDefault();
    setError("");

    // very simple validation
    const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!emailRegex.test(email.trim())) {
      setError("Please enter a valid email address.");
      return;
    }

    try {
      setStatus("loading");
      // TODO: Swap this with your email collection endpoint (Mailchimp, Klaviyo, Formspree, etc.)
      // Example for Formspree: await fetch("https://formspree.io/f/yourid", { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ email }) });
      await new Promise((r) => setTimeout(r, 800)); // fake latency
      setStatus("success");
      setEmail("");
    } catch (err) {
      setStatus("error");
      setError("Something went wrong. Please try again.");
    }
  };

  return (
    <main className="min-h-screen bg-black text-white flex items-center justify-center p-6">
      <div className="w-full max-w-5xl">
        {/* Header / Logo */}
        <header className="flex items-center justify-center mb-10">
          <img
            src="/fandrop-logo.png"
            alt="Fandrop logo"
            className="h-14 w-auto opacity-90"
          />
        </header>

        {/* Hero + Split Brand Panels */}
        <section className="rounded-2xl overflow-hidden border border-white/10 shadow-2xl">
          <div className="grid grid-cols-1 md:grid-cols-2">
            {/* Left: Marvel side */}
            <div className="relative bg-black/60 backdrop-blur-sm">
              <div className="p-8 md:p-12 h-full flex flex-col">
                <div className="flex-1">
                  <h2 className="text-3xl md:text-5xl font-black tracking-tight uppercase">Marvel</h2>
                  <p className="mt-4 text-sm md:text-base text-white/70 max-w-md">
                    Mini diorama scenes. 2" figures. Iconic artifacts. Art meets collectible.
                  </p>
                </div>
                <div className="pt-8 text-white/40 text-xs">© MARVEL. Used under license.</div>
              </div>
              {/* subtle vertical divider on mobile */}
              <div className="absolute right-0 top-0 h-full w-px bg-white/10 md:hidden" />
            </div>

            {/* Right: Star Wars side */}
            <div className="relative bg-black">
              <div className="p-8 md:p-12 h-full flex flex-col">
                <div className="flex-1">
                  <h2 className="text-3xl md:text-5xl font-black tracking-tight uppercase">Star Wars</h2>
                  <p className="mt-4 text-sm md:text-base text-white/70 max-w-md">
                    Cinematic moments re‑created as display‑ready, limited‑run sets.
                  </p>
                </div>
                <div className="pt-8 text-white/40 text-xs">™ & © Lucasfilm Ltd. Used under license.</div>
              </div>
              {/* Center divider on desktop */}
              <div className="hidden md:block absolute left-0 top-0 h-full w-px bg-white/10" />
            </div>
          </div>

          {/* Email capture bar */}
          <div className="border-t border-white/10 bg-white/5 p-6 md:p-8">
            <div className="md:flex md:items-end md:gap-6">
              <div className="md:flex-1">
                <h3 className="text-xl md:text-2xl font-semibold">Get notified when new drops land</h3>
                <p className="mt-2 text-sm text-white/70">Join the list for early access, reveals, and behind‑the‑scenes.</p>
              </div>

              <form onSubmit={onSubmit} className="mt-4 md:mt-0 w-full md:w-[420px]">
                <label htmlFor="email" className="sr-only">Email address</label>
                <div className="flex gap-2">
                  <input
                    id="email"
                    type="email"
                    value={email}
                    onChange={(e) => setEmail(e.target.value)}
                    placeholder="you@example.com"
                    className="flex-1 bg-black/60 border border-white/15 rounded-xl px-4 py-3 outline-none focus:ring-2 focus:ring-white/40 focus:border-white/30 placeholder:text-white/40"
                  />
                  <button
                    type="submit"
                    disabled={status === "loading" || status === "success"}
                    className="px-5 py-3 rounded-xl border border-white/20 hover:border-white/40 transition disabled:opacity-50 disabled:cursor-not-allowed"
                  >
                    {status === "loading" ? "Joining…" : status === "success" ? "Joined" : "Notify me"}
                  </button>
                </div>
                {error && <p className="mt-2 text-sm text-red-400">{error}</p>}
                {status === "success" && (
                  <p className="mt-2 text-sm text-green-300">Thanks! You're on the list.</p>
                )}
              </form>
            </div>

            <p className="mt-4 text-xs text-white/50">
              We respect your privacy. Unsubscribe anytime.
            </p>
          </div>
        </section>

        {/* Footer */}
        <footer className="mt-8 flex flex-col md:flex-row items-center justify-between gap-4 text-xs text-white/50">
          <div>© {new Date().getFullYear()} Fandrop. All rights reserved.</div>
          <nav className="flex items-center gap-4">
            <a href="#" className="hover:text-white/80">Privacy</a>
            <a href="#" className="hover:text-white/80">Terms</a>
            <a href="#" className="hover:text-white/80">Contact</a>
          </nav>
        </footer>
      </div>
    </main>
  );
}
