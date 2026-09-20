<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGnR2Endgx)" clip-rule="evenodd" class="tj_sx3-rb"/><defs><linearGradient id="SVGnR2Endgx" x1="18.226" x2="5.326" y1="2.147" y2="20.689" gradientUnits="userSpaceOnUse"><stop class="rlp60sb4c"/><stop offset=".253" class="g9cn6cb6i"/><stop offset=".497" class="ky-o6c4pf"/><stop offset=".75" class="q1a3ybc8v"/><stop offset=".999" class="la1q1sbut"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pulsechain" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g9cn6cb6i {
  stop-color: var(--svg-color--0080ff, #0080ff);
}

.ky-o6c4pf {
  stop-color: var(--svg-color--8000ff, #8000ff);
}

.la1q1sbut {
  stop-color: var(--svg-color--red, red);
}

.q1a3ybc8v {
  stop-color: var(--svg-color--e619e6, #e619e6);
}

.rlp60sb4c {
  stop-color: var(--svg-color--00eaff, #00eaff);
}

.tj_sx3-rb {
  fill-rule: evenodd;
  d: path("M21 13.04c0 .091-.02.179-.057.255l-3.86 7.21a.91.91 0 0 1-.794.495H7.71a.91.91 0 0 1-.794-.494l-3.86-7.212A.6.6 0 0 1 3 13.04c0-.298.224-.54.501-.54h4.235l1.074 1.966l.006.012a.48.48 0 0 0 .68.18l.012-.008a.54.54 0 0 0 .219-.323l1.367-5.702l1.175 9.18l.002.013c.043.289.292.489.563.449l.012-.002a.52.52 0 0 0 .404-.398l1.649-6.873l.677 1.24l.006.011a.5.5 0 0 0 .425.255H20.5c.277 0 .501.242.501.54M16.289 3c.327 0 .63.188.793.494l3.861 7.211a.6.6 0 0 1 .057.256c0 .298-.224.54-.501.54h-4.25l-1.073-1.966l-.007-.013a.5.5 0 0 0-.299-.236l-.012-.003c-.264-.067-.53.106-.599.39l-1.367 5.703l-1.174-9.18l-.002-.013a.53.53 0 0 0-.37-.437c-.267-.074-.54.1-.61.388l-1.649 6.873l-.676-1.24l-.007-.011a.5.5 0 0 0-.425-.255H3.5c-.277 0-.501-.242-.501-.54c0-.091.019-.178.056-.253l3.861-7.214A.91.91 0 0 1 7.711 3z");
}

</style>
