<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v0renrgmb"/><path class="g9-a5bsup"/><path class="j3t1fbcok"/><path class="r2hn0nart"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:masonry-outline-regular" /></template>
<style>
.g9-a5bsup {
  d: path("M13.5 4a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-4.5a2 2 0 0 1 -2 -2Z");
}

.j3t1fbcok {
  d: path("M2 15a2 2 0 0 1 2 -2h4.5a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r2hn0nart {
  d: path("M13.5 19.5A2.5 2.5 0 0 1 16 17h3.5a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5H16a2.5 2.5 0 0 1 -2.5 -2.5");
}

.v0renrgmb {
  d: path("M2 4a2 2 0 0 1 2 -2h4.5a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
