import React from "react"; import { Button } from "@/components/ui/button"; import { Card, CardContent } from "@/components/ui/card";

export default function TrustPowerSite() { return ( <div className="min-h-screen bg-black text-white font-sans"> {/* Header */} <header className="bg-zinc-900 p-6 shadow-md sticky top-0 z-50"> <div className="max-w-7xl mx-auto flex justify-between items-center"> <h1 className="text-2xl font-bold text-white">Trust Power</h1> <nav className="space-x-6"> <a href="#about" className="hover:text-zinc-400">About</a> <a href="#services" className="hover:text-zinc-400">Services</a> <a href="#policy" className="hover:text-zinc-400">Policy</a> <a href="#contact" className="hover:text-zinc-400">Contact</a> </nav> </div> </header>

{/* Hero Section */}
  <section className="text-center py-32 bg-gradient-to-b from-zinc-900 to-black">
    <h2 className="text-5xl font-bold mb-4">Powering Bangladesh</h2>
    <p className="text-zinc-400 max-w-2xl mx-auto text-lg">
      Trust Power Service and Technology BD – Dedicated to reliable energy solutions, service excellence, and innovation.
    </p>
    <Button className="mt-8 text-black bg-white hover:bg-zinc-200 transition">Explore Our Services</Button>
  </section>

  {/* About Section */}
  <section id="about" className="py-24 px-4 bg-black">
    <div className="max-w-5xl mx-auto text-center">
      <h3 className="text-3xl font-semibold mb-4">About Us</h3>
      <p className="text-zinc-400 text-lg">
        Founded by a visionary, taken over by family – Trust Power is more than just a name. We're the silent power behind your everyday energy. From backup systems to smart technology, we drive reliability.
      </p>
    </div>
  </section>

  {/* Services */}
  <section id="services" className="py-24 px-4 bg-zinc-950">
    <div className="max-w-6xl mx-auto">
      <h3 className="text-3xl font-semibold mb-10 text-center">Our Services</h3>
      <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
        <Card className="bg-zinc-800 text-white">
          <CardContent className="p-6">
            <h4 className="text-xl font-bold mb-2">Backup Power Solutions</h4>
            <p className="text-zinc-400">Generators, UPS, and hybrid systems for industrial & home use.</p>
          </CardContent>
        </Card>
        <Card className="bg-zinc-800 text-white">
          <CardContent className="p-6">
            <h4 className="text-xl font-bold mb-2">Maintenance & Support</h4>
            <p className="text-zinc-400">24/7 on-call support and preventive maintenance for all installations.</p>
          </CardContent>
        </Card>
        <Card className="bg-zinc-800 text-white">
          <CardContent className="p-6">
            <h4 className="text-xl font-bold mb-2">Smart Technology Integration</h4>
            <p className="text-zinc-400">IoT-based monitoring & control systems for power infrastructure.</p>
          </CardContent>
        </Card>
      </div>
    </div>
  </section>

  {/* Policies */}
  <section id="policy" className="py-24 px-4 bg-black">
    <div className="max-w-5xl mx-auto text-center">
      <h3 className="text-3xl font-semibold mb-4">Our Policies</h3>
      <p className="text-zinc-400 text-lg mb-6">
        Trust, transparency, and responsibility. We maintain strict confidentiality with customer data, ensure ethical service practices, and operate with integrity in all dealings.
      </p>
    </div>
  </section>

  {/* Contact */}
  <section id="contact" className="py-24 px-4 bg-zinc-950">
    <div className="max-w-4xl mx-auto text-center">
      <h3 className="text-3xl font-semibold mb-4">Contact Us</h3

