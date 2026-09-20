<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ga97lpb2d"/><path class="g_14gdcpn"/><path class="u83rpxb8q"/><path class="pdgwdvrql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:policy-list-outline-regular" /></template>
<style>
.g_14gdcpn {
  d: path("M15 9h7");
}

.ga97lpb2d {
  d: path("M3 5h9v6l-4.5 4.5L3 11Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pdgwdvrql {
  d: path("M15 17h7");
}

.u83rpxb8q {
  d: path("M15 13h7");
}

</style>
