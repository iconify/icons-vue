<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x_9dq4bdy"/><path clip-rule="evenodd" class="oxc64zbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:swatch-book-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oxc64zbus {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 17L2 3C2 2.4477 2.4477 2 3 2L11 2C11.5523 2 12 2.4477 12 3L12 17C12 19.7614 9.7614 22 7 22C4.2386 22 2 19.7614 2 17ZM6 17C6 17.5523 6.4477 18 7 18C7.5523 18 8 17.5523 8 17C8 16.4477 7.5523 16 7 16C6.4477 16 6 16.4477 6 17Z");
  stroke: none;
}

.x_9dq4bdy {
  d: path("M10.0642 19.5712L19.0632 8.8465L12.9348 3.7042L11 6.0101M7.6946 20.9392L21 18.5931L19.6109 10.7147L17.1284 11.1524");
}

</style>
