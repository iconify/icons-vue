<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iv0y2h-kx"/><path class="rcb4fqbjn"/><path class="nnfag_b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visual-regression" /></template>
<style>
.iv0y2h-kx {
  d: path("M3 5.5v12q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T5 19.5h2.872");
}

.nnfag_b0m {
  fill: currentColor;
  d: path("M14 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.rcb4fqbjn {
  d: path("M6.5 16.5H6v-14h12V11m-8.5 6c1.5-2.25 3.5-3.5 6-3.5s4.5 1.25 6 3.5c-1.5 2.25-3.5 3.5-6 3.5s-4.5-1.25-6-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
