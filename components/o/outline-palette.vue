<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-eufbvc"/><circle class="xrvvu0fts"/><circle class="t3avdfb0o"/><circle class="uqsohbb5z"/><circle class="tnadvnpqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-palette" /></template>
<style>
.t3avdfb0o {
  cx: 9.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: currentColor;
}

.tnadvnpqb {
  cx: 17.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

.uqsohbb5z {
  cx: 14.5px;
  cy: 7.5px;
  r: 1.5px;
  fill: currentColor;
}

.ux-eufbvc {
  fill: currentColor;
  d: path("M12 22C6.49 22 2 17.51 2 12S6.49 2 12 2s10 4.04 10 9c0 3.31-2.69 6-6 6h-1.77c-.28 0-.5.22-.5.5c0 .12.05.23.13.33c.41.47.64 1.06.64 1.67A2.5 2.5 0 0 1 12 22m0-18c-4.41 0-8 3.59-8 8s3.59 8 8 8c.28 0 .5-.22.5-.5a.54.54 0 0 0-.14-.35c-.41-.46-.63-1.05-.63-1.65a2.5 2.5 0 0 1 2.5-2.5H16c2.21 0 4-1.79 4-4c0-3.86-3.59-7-8-7");
}

.xrvvu0fts {
  cx: 6.5px;
  cy: 11.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
