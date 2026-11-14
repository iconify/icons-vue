<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5opiz3rb"/><path class="w6_4-b4ec"/><path class="gx2_em63e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:staging-home" /></template>
<style>
.gx2_em63e {
  d: path("M14 21v-3.5a1.25 1.25 0 0 1 2.5 0V19H19v-1.5a1.25 1.25 0 0 1 2.5 0V21Z");
}

.i5opiz3rb {
  d: path("M11.223 19.5H2.5V10L11 3l8.5 7v1.677");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6_4-b4ec {
  d: path("M15.25 16.25V14.5h5v1.75");
}

</style>
