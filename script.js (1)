const button = document.getElementById("myButton");

button.addEventListener("click", () => {
  alert("Hello! Welcome to my website 🚀");
});

// Change background color on scroll
const sections = document.querySelectorAll("section");

window.addEventListener("scroll", () => {
  const scrollY = window.scrollY;
  
  sections.forEach((section, index) => {
    if (scrollY >= section.offsetTop - window.innerHeight / 2) {
      // Cycle background colors
      const colors = ["#0f172a", "#1e293b", "#334155"];
      section.style.backgroundColor = colors[index % colors.length];
    }
  });
});