<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q-kl3tvqp"/><path class="bfed4x5-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:server-console" /></template>
<style>
.bfed4x5-g {
  d: path("m7 14.5l2.25 2.25L7 19m5 0h4");
}

.q-kl3tvqp {
  d: path("M3 2.5h18V9H3Zm0 9.25h18v9.75H3Zm3.5-6h.01m4.49 0h6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
