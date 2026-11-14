<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ue-z101dq"/><path class="gsqewc7am"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poison-bottle" /></template>
<style>
.gsqewc7am {
  d: path("M8 13.5a4 4 0 0 1 8 0V16a1 1 0 0 1-1 1h-1v1.5h-4V17H9a1 1 0 0 1-1-1Zm2.25.5h.01m3.49 0h.01");
}

.ue-z101dq {
  d: path("M10 2.5h4V6c3.5 1 5 3.5 5 6.5V19a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 5 19v-6.5C5 9.5 6.5 7 10 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
