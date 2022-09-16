<h1 align="center">Hi 👋, I'm Vedat Önal</h1>
<h3 align="center">In Turkey, a computer engineering student, I work in the cyber security field.</h3>

- 🔭 I’m currently working on **Security**

<h3 align="left">Connect with me:</h3>
<p align="center">
<a href="https://twitter.com/vedatonal38" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="vedatonal38" height="30" width="40" /></a>
<a href="https://linkedin.com/in/vedat-%c3%b6nal-04004319b/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="vedat-%c3%b6nal-04004319b/" height="30" width="40" /></a>
<a href="https://fb.com/vedatonal38" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="vedatonal38" height="30" width="40" /></a>
<a href="https://instagram.com/vedatonal38" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="vedatonal38" height="30" width="40" /></a>
<a href="https://discord.gg/vedatonal38#9510" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/discord.svg" alt="vedatonal38#9510" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>

<p align="center"> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank"> <img src="https://cdn.worldvectorlogo.com/logos/microsoft-sql-server.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://sass-lang.com" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> <a href="https://www.selenium.dev" target="_blank"> <img src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" alt="selenium" width="40" height="40"/> </a> </p>

<p align="center"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=vedatonal38&show_icons=true&locale=en&layout=compact" alt="vedatonal38" /></p>

<p align="center">&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=vedatonal38&show_icons=true&locale=en" alt="vedatonal38" /></p>



<style>
  
div.highlight button {
  color: red;
  box-sizing: border-box;
  transition: 0.2s ease-out;
  cursor: pointer;
  user-select: none;
  background: rgba(0, 0, 0, 0.15);
  border: 1px solid rgba(0, 0, 0, 0);
  padding: 5px 10px;
  font-size: 0.8em;
  position: absolute;
  top:0;
  right: 0;
  border-radius: 0 0.15rem;
}
</style>
<div class="highlight">
  <code>systemctl daemon-reload <br>
systemctl enable kibana <br>
systemctl start kibana</code>
  <button>Copy</button>
</div>

<script>
// get the list of all highlight code blocks
const highlights = document.querySelectorAll("div.highlight")

highlights.forEach(div => {
  // create the copy button
  const copy = document.createElement("button")
  copy.innerHTML = "Copy"
  // add the event listener to each click
  copy.addEventListener("click", handleCopyClick)
  // append the copy button to each code block
  div.append(copy)
})

const copyToClipboard = str => {
  const el = document.createElement("textarea") // Create a <textarea> element
  el.value = str // Set its value to the string that you want copied
  el.setAttribute("readonly", "") // Make it readonly to be tamper-proof
  el.style.position = "absolute"
  el.style.left = "-9999px" // Move outside the screen to make it invisible
  document.body.appendChild(el) // Append the <textarea> element to the HTML document
  const selected =
    document.getSelection().rangeCount > 0 // Check if there is any content selected previously
      ? document.getSelection().getRangeAt(0) // Store selection if found
      : false // Mark as false to know no selection existed before
  el.select() // Select the <textarea> content
  document.execCommand("copy") // Copy - only works as a result of a user action (e.g. click events)
  document.body.removeChild(el) // Remove the <textarea> element
  if (selected) {
    // If a selection existed before copying
    document.getSelection().removeAllRanges() // Unselect everything on the HTML document
    document.getSelection().addRange(selected) // Restore the original selection
  }
}

function handleCopyClick(evt) {
  // get the children of the parent element
  const { children } = evt.target.parentElement
  // grab the first element (we append the copy button on afterwards, so the first will be the code element)
  // destructure the innerText from the code block
  const { innerText } = Array.from(children)[0]
  // copy all of the code to the clipboard
  copyToClipboard(innerText)
  // alert to show it worked, but you can put any kind of tooltip/popup to notify it worked
  alert(innerText)
}
</script>
