<template>
  <Layout class="w-full mx-auto">
    <div class="w-3/4 mx-auto">
      <h1 class="text-4xl font-bold" id="main">My Tools</h1>
      <p
        class="text-lg font-bold"
      >Here's a list of things I use for my day to day work and activities. I'll try to always update this list so it reflects the current tool I'm using at the moment.</p>
      <div>
        <h2 class="text-3xl my-4">Editor & Terminal ⌨️</h2>
        <ul class="text-xl">
          <li>
            <b>Editor:</b> VSCode
          </li>
          <li>
            <b>Color Theme:</b> I switch between
            <a href="https://marketplace.visualstudio.com/items?itemName=sdras.night-owl">Night Owl</a> by Sarah Drasner and
            <a
              href="https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode"
            >SynthWave '84</a> by Robb Owen
          </li>
          <li>
            <b>Coding Font:</b><a href="https://dank.sh/">  Dank Mono</a> by Phil Plückthun
          </li>
          <li>
            <b>Terminal:</b> I switch between ITerm and Hyper. I love them equally I guess?
          </li>
        </ul>
        <h2 class="text-3xl my-4">Desktop Apps 🖥️</h2>
        <ul class="text-xl">
          <li>Spectacle - Helps me manage my window arrangement.</li>
          <li>Adobe XD - use this for creating UI designs</li>
          <li>Slack - for communication and what not</li>
          <li>Discord - engaging with the dev community on Discord is fun!</li>
          <li>Rocket - a fun slack-like emoji app for Mac 🚀</li>
          <li>Hyper - useful terminal app for Mac</li>
          <li>ITerm - my default terminal before Hyper stole my heart</li>
          <li>Alfred - automate my workflow</li>
          <li>Notion - my diary for everything</li>
        </ul>
        <h2 class="text-3xl my-4">Recording 🎤📸</h2>
        <ul class="text-xl">
          <li>Screenflow - use this for screen recording and editing</li>
          <li>Final Cut Pro - edit my videos with this</li>
          <li>Canon G7X Markii - for making vlogs and videos that are not screen recorded</li>
          <li>Logitech C922 Pro Stream HD - mostly for my meetings and streams</li>
          <li>Shure BETA® 87A Vocal Microphone - love this mic!</li>
        </ul>
        <h2 class="text-3xl my-4">Desk Setup 👩‍💻💻</h2>
        <ul class="text-xl">
          <li>MacBook Pro 13" 2019 with macOS Mojave</li>
          <li>Samsung 27" LED Monitor with Eye saver mode</li>
          <li>Bose Soundlink Micro Speaker</li>
        </ul>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Uses',
    meta: [
      { name: 'title', content: 'Uses' }
    ],
  }
}
</script>

<style lang="scss" scoped>
 a {
  color: var(--link-color);
  background:
     linear-gradient(
       to bottom, var(--link-accent-color) 0%,
       var(--link-accent-color) 100%
     );
  background-position: 0 100%;
  background-repeat: repeat-x;
  background-size: 4px 4px;
  transition: background-size .5s;
}

 a:hover {
  background: var(--link-accent-color);
  color: var(--link-color);
  background-size: 4px 50px;
}
</style>