<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="po6vlitvx"/><circle class="alqc54g4m"/><path class="nwtbv1bng"/><path class="vgxb1zfsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-support-agent" /></template>
<style>
.alqc54g4m {
  cx: 15px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.nwtbv1bng {
  fill: currentColor;
  d: path("M18 11.03A6.04 6.04 0 0 0 12.05 6c-3.03 0-6.29 2.51-6.03 6.45a8.07 8.07 0 0 0 4.86-5.89c1.31 2.63 4 4.44 7.12 4.47");
}

.po6vlitvx {
  cx: 9px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.vgxb1zfsx {
  fill: currentColor;
  d: path("M20.99 12c-.11-5.37-4.31-9-8.99-9c-4.61 0-8.85 3.53-8.99 9H2v6h3v-5.81c0-3.83 2.95-7.18 6.78-7.29a7.007 7.007 0 0 1 7.22 7V19h-8v2h10v-3h1v-6z");
}

</style>
