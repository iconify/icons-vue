<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n7x-_ubqb"/><path class="hgwg5ebmo"/><path class="kowaom1sy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:threat-intel" /></template>
<style>
.hgwg5ebmo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11.25q1.875-3 4.5-3c2.625 0 3.25 1 4.5 3q-1.875 3-4.5 3c-2.625 0-3.25-1-4.5-3");
}

.kowaom1sy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.25h.01");
}

.n7x-_ubqb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l7.25 2.75v6c0 4.75-3 8.25-7.25 9.75c-4.25-1.5-7.25-5-7.25-9.75v-6Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
