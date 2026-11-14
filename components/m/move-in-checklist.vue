<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s0cplmwxo"/><path class="ir-1fb83r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:move-in-checklist" /></template>
<style>
.ir-1fb83r {
  d: path("M7 7.25L8.25 8.5l2-2.25m2.25 1h4M7 12.5l1.25 1.25l2-2.25m2.25 1h4M7 17.75L8.25 19l2-2.25m4.25 3a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3-1.25l3.75-3.75m-1.5 1.5l1.5 1.5");
}

.s0cplmwxo {
  d: path("M12 21.5H4.5v-19h15v10.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
