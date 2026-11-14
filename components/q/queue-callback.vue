<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="htsx9gb6j"/><path class="e03c9gpty"/><path class="qyspmebfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:queue-callback" /></template>
<style>
.e03c9gpty {
  d: path("M20.5 11V7.25a3 3 0 0 0-3-3H14");
}

.htsx9gb6j {
  d: path("M20.5 5v3.5L16 10l-1.5-2C12 9 9 12 8 14.5l2 1.5l-1.5 4.5H5a2 2 0 0 1-2-2c.5-8 7.5-15 15.5-15.5a2 2 0 0 1 2 2Z");
}

.qyspmebfq {
  d: path("m16 2.25l-2 2l2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
