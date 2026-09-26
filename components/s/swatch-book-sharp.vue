<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mj1i6js7i"/><path class="em8goyshd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:swatch-book-sharp" /></template>
<style>
.em8goyshd {
  fill: currentColor;
  d: path("M6 17C6 17.5523 6.4477 18 7 18C7.5523 18 8 17.5523 8 17C8 16.4477 7.5523 16 7 16C6.4477 16 6 16.4477 6 17Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mj1i6js7i {
  d: path("M3 17L3 3L11 3L11 17C11 19.2091 9.2091 21 7 21C4.7909 21 3 19.2091 3 17ZM10.0642 19.5712L19.0632 8.8465L12.9348 3.7042L11 6.0101M7.6946 20.9392L21 18.5931L19.6109 10.7147L17.1284 11.1524");
}

</style>
