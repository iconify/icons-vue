<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGPVlzvAjM)" class="x9f9lmb2b"/><defs><linearGradient id="SVGPVlzvAjM" x1="3" x2="19.446" y1="6.62" y2="19.179" gradientUnits="userSpaceOnUse"><stop class="maxvamb_o"/><stop offset="1" class="obi04sphw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nftart" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.maxvamb_o {
  stop-color: var(--svg-color--d6022a, #d6022a);
}

.obi04sphw {
  stop-color: var(--svg-color--3c08c3, #3c08c3);
}

.x9f9lmb2b {
  d: path("M5.813 4.125v6.188H3v3.374h1.547c.731 0 1.102-.933 1.266-1.783v7.971h3.374v-9.433l6.47 9.433h2.53v-6.187H21v-3.376h-1.547c-.731 0-1.102.934-1.266 1.784V4.125h-3.375v9.54l-6.525-9.54z");
}

</style>
