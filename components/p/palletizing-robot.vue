<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="txi5bepoz"/><path class="wj6guebei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:palletizing-robot" /></template>
<style>
.txi5bepoz {
  d: path("m3.5 21l1-2.5H8L9 21Zm2.75-2.5V11l6.25-6.5l5 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wj6guebei {
  d: path("M15 11.5V9h5v2.5m-6 0h7v5h-7Zm-1 8h8.5");
}

</style>
