<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un4cafd_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:perfect-binding" /></template>
<style>
.un4cafd_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21 5H7a3.5 3.5 0 0 0-3.5 3.5v7A3.5 3.5 0 0 0 7 19h14ZM9 5v14m3-9.25h9m-9 4.5h9M6.25 12h.01");
}

</style>
