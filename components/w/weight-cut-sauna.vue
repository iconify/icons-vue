<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zhn9hbb7k"/><path class="j04o-pb8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weight-cut-sauna" /></template>
<style>
.j04o-pb8z {
  d: path("M6.75 5c0 3.25 5 3.25 5 0m-4.5 11.75l1-2.75h2l1 2.75m5.25 4.75q-1.875-1.5 0-3t0-3m2.5 6q-1.875-1.5 0-3t0-3m2.5 6q-1.875-1.5 0-3c.5-.5.5-2 0-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhn9hbb7k {
  d: path("M16 11.685V8.5c0-1.25-.75-2-1.75-2.5l-2.5-1c0-3.25-5-3.25-5 0l-2.5 1c-1 .5-1.75 1.25-1.75 2.5v4H5v7h7.815m.685-1.815v-1m0-1.9V12.5h1.815");
}

</style>
