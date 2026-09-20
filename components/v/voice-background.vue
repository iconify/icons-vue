<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGGGV8derj)" class="r4i437pya"/><path clip-rule="evenodd" class="tjhldk64a"/><path class="crwvkkbck"/></g><defs><linearGradient id="SVGGGV8derj" x1="16.781" x2="5.073" y1="16.278" y2="8.066" gradientUnits="userSpaceOnUse"><stop class="zz_0stb2r"/><stop offset="1" class="prj1v9bte"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:voice-background" /></template>
<style>
.crwvkkbck {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.92 11.059v2.353h.55v-2.353zm.033-.4a.36.36 0 0 0 .254.094a.34.34 0 0 0 .25-.094a.33.33 0 0 0 .094-.236a.27.27 0 0 0-.094-.216a.35.35 0 0 0-.25-.09a.36.36 0 0 0-.254.095a.3.3 0 0 0-.094.22q.001.134.094.227m2.137 2.753c-.245 0-.462-.047-.655-.151a1.15 1.15 0 0 1-.597-1.026a1.14 1.14 0 0 1 .597-1.026c.189-.098.41-.15.654-.15c.222 0 .424.047.593.14q.256.13.391.392l-.414.244a.66.66 0 0 0-.574-.32a.76.76 0 0 0-.363.085a.6.6 0 0 0-.249.25a.77.77 0 0 0-.094.385c0 .146.033.278.094.386a.63.63 0 0 0 .25.245a.75.75 0 0 0 .682.01a.65.65 0 0 0 .254-.24l.414.235a.94.94 0 0 1-.39.404a1.23 1.23 0 0 1-.598.137zm2.47 0a1.4 1.4 0 0 1-.677-.151a1.2 1.2 0 0 1-.448-.423a1.2 1.2 0 0 1-.155-.603a1.12 1.12 0 0 1 .574-1.026c.189-.098.39-.15.621-.15c.226 0 .424.047.603.146c.174.094.315.235.414.414c.131.24.181.515.141.786h-1.812c.014.08.047.155.085.22c.061.104.15.189.268.245a.9.9 0 0 0 .396.085a.9.9 0 0 0 .352-.06a.7.7 0 0 0 .278-.19l.287.33a1 1 0 0 1-.39.283a1.5 1.5 0 0 1-.537.094m-.668-1.6a.8.8 0 0 0-.075.235h1.317a.62.62 0 0 0-.315-.47a.63.63 0 0 0-.344-.09a.7.7 0 0 0-.348.09a.63.63 0 0 0-.235.235m-5.647 1.6a1.3 1.3 0 0 1-.635-.151a1.16 1.16 0 0 1-.598-1.026a1.14 1.14 0 0 1 .598-1.026c.188-.098.395-.15.635-.15c.235 0 .452.047.635.15c.188.1.33.236.438.414c.103.175.16.377.16.612a1.15 1.15 0 0 1-.598 1.026q-.282.15-.635.15m0-.462q.198 0 .353-.084a.6.6 0 0 0 .244-.25a.8.8 0 0 0 .09-.38a.76.76 0 0 0-.094-.387a.6.6 0 0 0-.24-.25a.7.7 0 0 0-.353-.084a.63.63 0 0 0-.598.334a.8.8 0 0 0-.09.386a.75.75 0 0 0 .095.377a.64.64 0 0 0 .593.338M6.372 11.06l.988 2.353h.565l.988-2.353h-.518l-.743 1.74l-.72-1.74h-.565z");
}

.ft5dv1b6b {
  fill: none;
}

.prj1v9bte {
  stop-color: var(--svg-color--fc0c34, #fc0c34);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tjhldk64a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53c4.212 0 7.53-3.318 7.53-7.53S16.211 4.47 12 4.47S4.47 7.789 4.47 12s3.318 7.53 7.53 7.53m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.zz_0stb2r {
  stop-color: var(--svg-color--d7b1e3, #d7b1e3);
}

</style>
