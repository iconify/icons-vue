<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yjg3l6fqq"/><path class="afc32xb9r"/><path class="si_bombbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tuition-reimbursement" /></template>
<style>
.afc32xb9r {
  d: path("M6.5 10v3.5c0 1.75 9 1.75 9 0V10m3-2v4M15 18.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm2.75-.75v1.5M3.5 15.25c0 3 4 4.5 9 4.25");
}

.si_bombbc {
  d: path("m10.75 17.75l1.75 1.75l-1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjg3l6fqq {
  d: path("M3.5 8L11 4.25L18.5 8L11 11.75Z");
}

</style>
