<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj5ivp89r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pool-no-diving" /></template>
<style>
.nj5ivp89r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.5 4.5l-5.02 5.02m-5.165 2.692q-.134.123-.239.271q-.106.148-.179.314q-.072.166-.11.344q-.037.177-.037.359q0 .086.008.172t.026.169q.016.085.041.167t.058.162q.033.079.074.155t.088.147t.102.138t.116.127t.127.116q.066.054.138.102q.071.048.147.088q.076.041.155.074q.08.033.162.058t.167.041t.169.026t.172.008q.171 0 .338-.033t.325-.097t.3-.159q.143-.094.264-.213M3 19.5q2.25-2 4.5 0t4.5 0q1.303-1.158 2.605-.975M3.5 3.5l17 17");
}

</style>
