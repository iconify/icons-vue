<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="avkx56goc"/><path class="kn5qbsb2u"/><path class="b58_c5b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:potato-plant-sharp" /></template>
<style>
.avkx56goc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V6.5m0 .5c0-2.25-1.5-3.75-4-4.25c0 2.5 1.5 4 4 4.25Zm0 2c0-2.25 1.5-3.75 4-4.25c0 2.5-1.5 4-4 4.25Zm-9.25 3h18.5M12 12v2.75m0 0l-1.4.35l-1.35.9M12 14.75l1.8.45l.7 1.05");
}

.b58_c5b3h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 17.75h.01m9.99.5h.01m2.24 1h.01");
}

.kn5qbsb2u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15.5h6V20h-6zm10 .75h7v5h-7z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
