import React from "react";

export default function Home() {
  return (
    <main className="p-6 space-y-10 animate-fadeIn">
      <nav className="flex justify-between items-center py-4 border-b animate-slideIn">
        <h1 className="text-2xl font-bold">Greatbridge Technologies</h1>
        <ul className="flex gap-6 text-sm text-gray-700">
          <li><a href="#services">Services</a></li>
          <li><a href="#portfolio">Portfolio</a></li>
          <li><a href="#blog">Blog</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>

      <section className="text-center space-y-4">
        <h2 className="text-4xl font-bold">Empowering Learning & Technology</h2>
        <p className="text-lg text-gray-600">Web Developer | Tutor | IT Expert | Data Clerk</p>
        <button className="mt-4 px-4 py-2 border rounded hover:bg-gray-200">Hire Me</button>
      </section>

      <section id="services" className="grid grid-cols-1 md:grid-cols-2 gap-6">
        <div className="p-4 border rounded shadow">
          <h3 className="text-2xl font-semibold mb-2">Web Development</h3>
          <p>I build responsive websites, web apps, and help businesses go digital.</p>
        </div>
        <div className="p-4 border rounded shadow">
          <h3 className="text-2xl font-semibold mb-2">Tutoring</h3>
          <p>Math, Geography, and IT lessons for students and professionals.</p>
        </div>
        <div className="p-4 border rounded shadow">
          <h3 className="text-2xl font-semibold mb-2">IT Services</h3>
          <p>Data entry, HELB/KUCCPS/KRA applications, and online account setup.</p>
        </div>
        <div className="p-4 border rounded shadow">
          <h3 className="text-2xl font-semibold mb-2">Online Income Support</h3>
          <p>I train and guide students on how to earn online using various platforms.</p>
        </div>
      </section>

      <section id="portfolio" className="space-y-4">
        <h2 className="text-2xl font-bold">Portfolio</h2>
        <p className="text-gray-700">Explore some of my recent projects and tutoring results.</p>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div className="p-4 border rounded shadow">Project 1 – Web App for Students</div>
          <div className="p-4 border rounded shadow">Project 2 – Education Blog Platform</div>
        </div>
      </section>

      <section id="blog" className="space-y-4">
        <h2 className="text-2xl font-bold">Blog</h2>
        <p className="text-gray-700">Tips, tutorials, and updates on learning and tech.</p>
        <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
          <div className="p-4 border rounded shadow">How to Apply for HELB: Step-by-step</div>
          <div className="p-4 border rounded shadow">Top 5 Online Gigs for Students</div>
        </div>
      </section>

      <section id="contact" className="text-center space-y-4">
        <h2 className="text-2xl font-bold">Contact Me</h2>
        <p>Phone: +254 712 345678</p>
        <p>Email: info@greatbridge.co.ke</p>
        <p>Website: www.greatbridge.co.ke</p>
        <a href="https://wa.me/254712345678" target="_blank" rel="noopener noreferrer">
          <button className="border px-4 py-2 rounded hover:bg-green-100">Chat on WhatsApp</button>
        </a>
        <a href="https://calendly.com/yourname/session" target="_blank" rel="noopener noreferrer">
          <button className="border px-4 py-2 rounded hover:bg-blue-100">Book a Session</button>
        </a>
      </section>
    </main>
  );
}
