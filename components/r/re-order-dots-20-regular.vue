<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="qzaz7mb2l"/><path class="sm2gfl2oq"/><path class="kdntf77di"/><path class="lug5_vtws"/><path class="m-unaqbfy"/><path class="bx5abw3hf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-20-regular" /></template>
<style>
.bx5abw3hf {
  d: path("M13 17a1 1 0 1 0 0-2a1 1 0 0 0 0 2z");
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.kdntf77di {
  d: path("M8 16a1 1 0 1 1-2 0a1 1 0 0 1 2 0z");
  fill: currentColor;
}

.lug5_vtws {
  d: path("M13 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2z");
  fill: currentColor;
}

.m-unaqbfy {
  d: path("M14 10a1 1 0 1 1-2 0a1 1 0 0 1 2 0z");
  fill: currentColor;
}

.qzaz7mb2l {
  d: path("M7 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2z");
  fill: currentColor;
}

.sm2gfl2oq {
  d: path("M7 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2z");
  fill: currentColor;
}

</style>
