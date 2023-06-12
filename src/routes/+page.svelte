<h1 class="text-3xl font-bold w-full pt-5 px-5 text-center md:text-left md:pt-20 md:px-20">
    Say hi to Serge.
</h1>

<h1 class="text-xl font-light w-full px-5 text-center  md:pt-2 md:text-left md:px-20">
    Your self-hosted personal assistant.
</h1>
  
<h1 class="text-xl font-light w-full px-5 text-center pb-5 md:text-left md:px-20 md:pb-20">
    No remote API, no data collection, no ads.
</h1>

<div class="mx-auto px-3">
    <video controls class="max-w-3xl w-full border rounded-md mx-auto border-slate-400 my-10 shadow-lg" src="/demo.webm">
        <track kind="captions" />
    </video>
</div>

<div class="divider max-w-3xl mx-auto"></div>

<h1 class="text-md w-full text-center mt-10 mb-5">
    Get started with a single command.
</h1>   

<div class="mx-auto px-3">
    <div class="mockup-code w-fit max-w-full mx-auto mt-1 shadow-lg">
        <pre data-prefix="$"><code>docker run -d \
         -v weights:/usr/src/app/weights -v datadb:/data/db/ \
         -p 8008:8008 ghcr.io/serge-chat/serge:latest
        </code></pre> 
        <pre data-prefix=">" class="text-success"><code>Done! Navigate to <a class="underline" href=http://localhost:8008>http://localhost:8008</a> to talk to Serge.</code></pre>
      </div>
</div>
  

  <!-- community sections, buttons for github and discord -->

<h1 class="text-md w-full text-center pt-16">
Join us on GitHub or Discord!
</h1>   

<div class="flex flex-row justify-center pt-2">
    <a href="https://github.com/nsarrazin/serge" target="_blank" rel="noopener noreferrer">
        <img src="https://img.shields.io/github/stars/nsarrazin/serge?style=flat" alt="GitHub stars">
    </a>
    <div class="w-5"></div>
    <a href="https://discord.gg/62Hc6FEYQH" target="_blank" rel="noopener noreferrer">
        <img src="https://img.shields.io/discord/1088427963801948201?label=Discord&logo=Discord&style=flat" alt="Discord">
    </a>
</div>

<div class="h-10"/>

<center>
    <a class="text-slate-500" href="mailto:contact@serge.chat">contact@serge.chat</a>
</center>

<div class="h-10"/>

<style lang="postcss">
:global(html) {
    background-color: theme(colors.gray.100);
}
</style>
