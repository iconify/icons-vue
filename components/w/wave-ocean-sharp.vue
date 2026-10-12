<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vkknvicwm"/><path class="edttvfi7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wave-ocean-sharp" /></template>
<style>
.edttvfi7c {
  d: path("M12.75 18.25c1.25 0 1.25-1 2.5-1s1.25 1 2.5 1s1.25-1 2.5-1m-7.5 4h8.5");
}

.vkknvicwm {
  d: path("M2.75 21.25C2.75 11 8.5 4.75 15 4.75c3.6 0 6.25 2.4 6.25 5.75V13h-2.5c-1.5 0-2-1.25-3.5-1.25c-2.75 0-5.75 3.75-5.75 9.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
