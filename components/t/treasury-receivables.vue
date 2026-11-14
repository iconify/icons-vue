<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0hwjnfqr"/><path class="w1jhd3b_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-receivables" /></template>
<style>
.g0hwjnfqr {
  d: path("M12.7 21.5H4.5v-19h15v10.1M8 6.5h3.5M8 10h8m-8 3.5h4.7M8 17h2.5M21 15l-5.25 5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1jhd3b_q {
  d: path("M15.5 16.25v4.25h4.25");
}

</style>
