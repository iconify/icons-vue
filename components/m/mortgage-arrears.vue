<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pklt6v8oy"/><path class="ofp0jdbkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-arrears" /></template>
<style>
.ofp0jdbkc {
  d: path("M16 7V4h2v4.75m0 5.75v4m0 2.75h.01");
}

.pklt6v8oy {
  d: path("M15.16 20.5H4v-10l8-7l8 7v1.24");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
