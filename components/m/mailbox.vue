<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yk4u9euhl"/><path class="d19wpd14k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mailbox" /></template>
<style>
.d19wpd14k {
  d: path("M7.5 7a4.5 4.5 0 0 1 4.5 4.5V18m3.5-7V3.5H19v3h-3.5M12 18v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yk4u9euhl {
  d: path("M7.5 7h9a4.5 4.5 0 0 1 4.5 4.5V18H3v-6.5A4.5 4.5 0 0 1 7.5 7Z");
}

</style>
