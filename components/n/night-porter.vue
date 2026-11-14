<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k8foptb4o"/><path class="budle8bnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:night-porter" /></template>
<style>
.budle8bnq {
  d: path("M12.05 18h-4.8V8h5v8.8M8.5 8V5H11v3M5.5 20.75h.01m5.49 0h.01m7.99-6A3.5 3.5 0 1 0 21.75 19A2.75 2.75 0 0 1 19 14.75Z");
}

.k8foptb4o {
  d: path("M2.5 3h2v15H12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
