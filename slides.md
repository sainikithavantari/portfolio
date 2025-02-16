---
theme: seriph
background: 'linear-gradient(150deg, #1a1a2e 0%, #16213e 100%)'
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  Portfolio Resume - Created with Slidev
drawings:
  persist: false
css: unocss
transition: slide-left
---

# SAINIKITHA VANTARI
### Software Engineer

<div class="pt-8">
  <img
    src="https://avatars.githubusercontent.com/u/107259970?v=4"
    class="w-32 h-32 rounded-full mx-auto mb-4 border-4 border-blue-500"
    alt="Profile Picture"
  />
</div>

<div class="pt-4 flex justify-center">
  <div class="px-4 py-2 rounded cursor-pointer bg-white bg-opacity-10">
    Specializing in Autonomous Systems, Computer Vision, and Machine Learning
  </div>
</div>

<div class="mt-12 flex flex-wrap justify-center gap-4">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors flex items-center gap-2"
    @click="$slidev.nav.go(3)"
  >
    <carbon-education class="text-xl" /> Education
  </button>
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors flex items-center gap-2"
    @click="$slidev.nav.go(2)"
  >
    <carbon-skill-level class="text-xl" /> Skills
  </button>
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors flex items-center gap-2"
    @click="$slidev.nav.go(4)"
  >
    <carbon-development class="text-xl" /> Projects
  </button>
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors flex items-center gap-2"
    @click="$slidev.nav.go(6)"
  >
    <carbon-email class="text-xl" /> Contact
  </button>
</div>

<div class="abs-br m-6 flex gap-2">
  <div class="text-sm opacity-50">
    <carbon-email class="inline-block mr-1" /> sainikithavantari@gmail.com
  </div>
</div>

---
layout: two-cols
---

# Profile

<div class="mr-4">
  <img
    src="https://images.unsplash.com/photo-1571171637578-41bc2dd41cd2?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
    class="w-full rounded-lg mb-4 shadow-lg"
    alt="Computer Vision"
  />
  
  <p class="mb-4">
    Results-driven Software Engineer with expertise in autonomous systems, computer vision, machine learning, and robotics. Skilled in algorithm development, perception, behavior prediction, and real-time system optimization.
  </p>
  
  <p class="mb-4">
    🌟 Core Competencies:
    - Algorithm Development
    - Computer Vision & ML
    - Statistical Modeling
    - Scalable AI Solutions
  </p>
</div>

::right::

<div class="pl-4 pt-12">
  <div class="rounded-lg bg-white bg-opacity-10 p-4 mb-4">
    <h3 class="text-blue-400 mb-2">Location</h3>
    Kearny, NJ
  </div>
  
  <div class="rounded-lg bg-white bg-opacity-10 p-4">
    <h3 class="text-blue-400 mb-2">Contact</h3>
    +1 551-229-8340
  </div>
  
  <img
    src="https://images.unsplash.com/photo-1555949963-aa79dcee981c?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
    class="w-full rounded-lg mt-4 shadow-lg"
    alt="Programming"
  />
</div>

<div class="fixed bottom-4 right-4 left-4 flex justify-center">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors"
    @click="$slidev.nav.go(0)"
  >
    Back to Menu
  </button>
</div>

---
layout: default
---

# Technical Skills

<div class="grid grid-cols-2 gap-4 mt-4">
  <div class="skill-category">
    <img
      src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-full h-48 object-cover rounded-lg mb-4 shadow-lg"
      alt="Programming Skills"
    />
    <h3 class="text-blue-400 mb-2">Programming Languages</h3>
    <div class="space-y-2">
      <div class="flex items-center">
        <div class="w-24">Python</div>
        <div class="flex-1 bg-gray-700 rounded-full h-2">
          <div class="bg-blue-500 rounded-full h-2" style="width: 95%"></div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="w-24">C++</div>
        <div class="flex-1 bg-gray-700 rounded-full h-2">
          <div class="bg-blue-500 rounded-full h-2" style="width: 90%"></div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="w-24">SQL</div>
        <div class="flex-1 bg-gray-700 rounded-full h-2">
          <div class="bg-blue-500 rounded-full h-2" style="width: 85%"></div>
        </div>
      </div>
    </div>
  </div>

  <div class="skill-category">
    <img
      src="https://images.unsplash.com/photo-1633356122544-f134324a6cee?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-full h-48 object-cover rounded-lg mb-4 shadow-lg"
      alt="Frameworks and Tools"
    />
    <h3 class="text-blue-400 mb-2">Frameworks & Tools</h3>
    <div class="space-y-2">
      <div class="flex items-center">
        <div class="w-24">OpenCV</div>
        <div class="flex-1 bg-gray-700 rounded-full h-2">
          <div class="bg-blue-500 rounded-full h-2" style="width: 95%"></div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="w-24">PyTorch</div>
        <div class="flex-1 bg-gray-700 rounded-full h-2">
          <div class="bg-blue-500 rounded-full h-2" style="width: 90%"></div>
        </div>
      </div>
      <div class="flex items-center">
        <div class="w-24">TensorFlow</div>
        <div class="flex-1 bg-gray-700 rounded-full h-2">
          <div class="bg-blue-500 rounded-full h-2" style="width: 85%"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="fixed bottom-4 right-4 left-4 flex justify-center">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors"
    @click="$slidev.nav.go(0)"
  >
    Back to Menu
  </button>
</div>

---
layout: default
---

# Education

<div class="grid grid-cols-2 gap-8 mt-4">
  <div class="education-item bg-white bg-opacity-10 p-6 rounded-lg">
    <img
      src="https://www.sacredheart.edu/media/shu-media/news-stories/2020/october/SHU-Campus-Fall-2020.jpg"
      class="w-full h-48 object-cover rounded-lg mb-4 shadow-lg"
      alt="Sacred Heart University"
    />
    <h3 class="text-blue-400 mb-2">Master of Science</h3>
    <p class="text-lg">Computer Science</p>
    <p class="text-sm text-gray-400">Sacred Heart University</p>
    <p class="text-sm">Fairfield, CT | December 2024</p>
  </div>

  <div class="education-item bg-white bg-opacity-10 p-6 rounded-lg">
    <img
      src="https://jntuh.ac.in/images/slider/slide1.jpg"
      class="w-full h-48 object-cover rounded-lg mb-4 shadow-lg"
      alt="JNTU Hyderabad"
    />
    <h3 class="text-blue-400 mb-2">Bachelor of Engineering</h3>
    <p class="text-lg">Computer Science</p>
    <p class="text-sm text-gray-400">Jawaharlal Nehru Technological University</p>
    <p class="text-sm">Hyderabad, India | August 2023</p>
  </div>
</div>

<div class="fixed bottom-4 right-4 left-4 flex justify-center">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors"
    @click="$slidev.nav.go(0)"
  >
    Back to Menu
  </button>
</div>

---
layout: default
---

# Projects

<div class="space-y-4">
  <div class="project-card bg-white bg-opacity-10 rounded-lg p-4">
    <div class="flex gap-4">
      <img
        src="https://images.unsplash.com/photo-1576678927484-cc907957088c?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
        class="w-48 h-32 object-cover rounded-lg shadow-lg"
        alt="Athlete Performance Analytics"
      />
      <div>
        <h3 class="text-blue-400 mb-2">Computer Vision-based Athlete Performance Analytics</h3>
        <p class="text-sm text-gray-400">Sacred Heart University | April 2024 – December 2024</p>
        <ul class="text-sm mt-2">
          <li>Designed and developed a Python-based analytics tool for tracking athlete movements with 90% accuracy</li>
          <li>Integrated pose estimation algorithms to deliver actionable insights</li>
          <li>Utilized statistical modeling for performance metrics analysis</li>
        </ul>
        <div class="flex gap-2 mt-3">
          <span class="text-xs bg-blue-500 px-2 py-1 rounded">Python</span>
          <span class="text-xs bg-green-500 px-2 py-1 rounded">OpenCV</span>
          <span class="text-xs bg-purple-500 px-2 py-1 rounded">Jupyter</span>
        </div>
      </div>
    </div>
  </div>

  <div class="project-card bg-white bg-opacity-10 rounded-lg p-4">
    <div class="flex gap-4">
      <img
        src="https://images.unsplash.com/photo-1549317661-bd32c8ce0db2?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
        class="w-48 h-32 object-cover rounded-lg shadow-lg"
        alt="Lane Detection"
      />
      <div>
        <h3 class="text-blue-400 mb-2">Lane Detection for Autonomous Driving</h3>
        <p class="text-sm text-gray-400">JNTU | January 2022 – May 2023</p>
        <ul class="text-sm mt-2">
          <li>Created a lane detection system with 95% accuracy for self-driving applications</li>
          <li>Optimized computer vision algorithms for real-time deployment</li>
        </ul>
        <div class="flex gap-2 mt-3">
          <span class="text-xs bg-yellow-500 px-2 py-1 rounded">OpenCV</span>
          <span class="text-xs bg-red-500 px-2 py-1 rounded">Python</span>
          <span class="text-xs bg-blue-500 px-2 py-1 rounded">Cloud</span>
        </div>
      </div>
    </div>
  </div>
</div>

<div class="fixed bottom-4 right-4 left-4 flex justify-center">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors"
    @click="$slidev.nav.go(0)"
  >
    Back to Menu
  </button>
</div>

---
layout: center
class: "text-center"
---

# Career Strengths

<div class="grid grid-cols-2 gap-4 mt-8">
  <div class="strength-item bg-white bg-opacity-10 p-4 rounded-lg">
    <img
      src="https://images.unsplash.com/photo-1533750349088-cd871a92f312?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-full h-32 object-cover rounded-lg mb-4 shadow-lg"
      alt="Problem Solving"
    />
    <h3 class="text-blue-400 mb-2">Problem-Solving</h3>
    <p class="text-sm">Ability to analyze complex technical challenges and implement efficient solutions</p>
  </div>
  
  <div class="strength-item bg-white bg-opacity-10 p-4 rounded-lg">
    <img
      src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-full h-32 object-cover rounded-lg mb-4 shadow-lg"
      alt="Technical Adaptability"
    />
    <h3 class="text-blue-400 mb-2">Technical Adaptability</h3>
    <p class="text-sm">Rapid learning and integration of new AI/ML methodologies and frameworks</p>
  </div>
  
  <div class="strength-item bg-white bg-opacity-10 p-4 rounded-lg">
    <img
      src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-full h-32 object-cover rounded-lg mb-4 shadow-lg"
      alt="Collaboration"
    />
    <h3 class="text-blue-400 mb-2">Collaboration</h3>
    <p class="text-sm">Effectively translates technical insights to diverse stakeholders</p>
  </div>
  
  <div class="strength-item bg-white bg-opacity-10 p-4 rounded-lg">
    <img
      src="https://images.unsplash.com/photo-1485827404703-89b55fcc595e?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-full h-32 object-cover rounded-lg mb-4 shadow-lg"
      alt="Innovation"
    />
    <h3 class="text-blue-400 mb-2">Innovation</h3>
    <p class="text-sm">Designs and optimizes commercially viable AI-driven service tools</p>
  </div>
</div>

<div class="fixed bottom-4 right-4 left-4 flex justify-center">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors"
    @click="$slidev.nav.go(0)"
  >
    Back to Menu
  </button>
</div>

---
layout: center
class: "text-center"
---

# Let's Connect!

<div class="grid grid-cols-3 gap-4 mt-8">
  <div class="contact-item">
    <img
      src="https://images.unsplash.com/photo-1557200134-90327ee9fafa?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-32 h-32 object-cover rounded-full mx-auto mb-4 shadow-lg"
      alt="Email"
    />
    <carbon-email class="text-4xl mb-2 mx-auto text-blue-400"/>
    <p class="text-sm">sainikithavantari@gmail.com</p>
  </div>
  
  <div class="contact-item">
    <img
      src="https://images.unsplash.com/photo-1523966211575-eb4a01e7dd51?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-32 h-32 object-cover rounded-full mx-auto mb-4 shadow-lg"
      alt="Phone"
    />
    <carbon-phone class="text-4xl mb-2 mx-auto text-blue-400"/>
    <p class="text-sm">+1 551-229-8340</p>
  </div>
  
  <div class="contact-item">
    <img
      src="https://images.unsplash.com/photo-1581287053822-fd7bf4f4bfec?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3"
      class="w-32 h-32 object-cover rounded-full mx-auto mb-4 shadow-lg"
      alt="Location"
    />
    <carbon-location class="text-4xl mb-2 mx-auto text-blue-400"/>
    <p class="text-sm">Kearny, NJ</p>
  </div>
</div>

<div class="fixed bottom-4 right-4 left-4 flex justify-center">
  <button 
    class="px-6 py-2 rounded-full cursor-pointer bg-blue-500 hover:bg-blue-600 transition-colors"
    @click="$slidev.nav.go(0)"
  >
    Back to Menu
  </button>
</div>

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}

button {
  color: white;
  font-size: 0.875rem;
  font-weight: 500;
}

button:disabled {
  opacity: 0.5;
  cursor: not-allowed;
}
</style>