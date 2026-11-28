<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amud_jbmq"/><path clip-rule="evenodd" class="y47bv3btj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-blend-fill" /></template>
<style>
.amud_jbmq {
  d: path("M3 12V4C3 3.448 3.4477 3 4 3H12M7 16V10C7 8.343 8.3431 7 10 7H16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y47bv3btj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.2426 11.757C21.3273 12.842 22 14.343 22 16C22 19.314 19.3137 22 16 22C12.6863 22 10 19.314 10 16C10 12.686 12.6863 10 16 10C17.6566 10 19.1579 10.673 20.2426 11.757Z");
  stroke: none;
}

</style>
