<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pnz9d-m6o"/><path class="edz-czr1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nft-badge" /></template>
<style>
.edz-czr1x {
  d: path("m8.75 14l-1.5 6.75l2.5-1.25L12 20.75l2.25-1.25l2.5 1.25l-1.5-6.75M12 5.75l.882 1.786l1.971.287l-1.426 1.391l.336 1.963L12 10.25l-1.763.927l.336-1.963l-1.426-1.391l1.971-.287Z");
}

.pnz9d-m6o {
  d: path("M5.75 8.75a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
