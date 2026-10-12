<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="f6ynkejbz"/><path class="i780oo3eq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:orchid-sharp" /></template>
<style>
.f6ynkejbz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5c1.9-.9 1.9-5.75 0-5.75S10.1 7.6 12 8.5Zm-2.25 2.35c.14-3.46-5.45-5.5-6.58-2.39c-1.13 3.1 4.46 5.13 6.58 2.39Zm4.5 0c2.12 2.74 7.71.71 6.58-2.39c-1.13-3.11-6.72-1.07-6.58 2.39Zm-3.75 2.9c-2.31-.04-5.11 5.21-3.29 6.18s4.62-4.28 3.29-6.18Zm3 0c-1.33 1.9 1.47 7.15 3.29 6.18s-.98-6.22-3.29-6.18Z");
}

.i780oo3eq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
