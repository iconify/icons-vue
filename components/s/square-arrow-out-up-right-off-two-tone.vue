<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fm3h4hboh"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-out-up-right-off-two-tone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.fm3h4hboh {
  stroke-opacity: 0.4;
  d: path("M7 7L6 7C4.3431 7 3 8.3431 3 10L3 18C3 19.6569 4.3431 21 6 21L14 21C15.6569 21 17 19.6569 17 18L17 17M14.8284 9.1716L20.5 3.5M13 3L20.5 3C20.7761 3 21 3.2239 21 3.5L21 11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
