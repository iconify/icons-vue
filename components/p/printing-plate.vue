<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h140qcb6l"/><path class="y8p9kxxre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:printing-plate" /></template>
<style>
.h140qcb6l {
  d: path("M3.5 4H17l3.5 3.5V20h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y8p9kxxre {
  d: path("M14.5 16.5v-9h-3a2.25 2.25 0 0 0 0 4.5h3M12 12l-2.5 4.5m-3-4.5h.01m11.24 0h.01");
}

</style>
