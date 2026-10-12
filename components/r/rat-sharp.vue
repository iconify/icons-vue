<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="md7qevb1h"/><path class="w6hdifbma"/><path class="w722ch5gx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rat-sharp" /></template>
<style>
.md7qevb1h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13v-.767l.75-.333l3-1.4c1.5-1.75 3.75-2.75 6.25-2.75c3.75 0 6.25 2.5 6.25 5.75c0 2.25-1.5 3.75-3.75 3.75h-7.5C6 17.25 4.5 15.5 3.4 14l-.65-.406z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w6hdifbma {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 9.25L7.125 5.875L10.5 7m8.5 6.75l2.25.75V17c0 2-1.5 3.25-3.5 3.5M8 17.25v2.25m6-2.25v2.25");
}

.w722ch5gx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 11.75h.01");
}

</style>
