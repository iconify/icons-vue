<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="alqc54g4m"/><circle class="po6vlitvx"/><path class="s6zu9-z9k"/><path class="kr63tmw5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-garage" /></template>
<style>
.alqc54g4m {
  cx: 15px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.kr63tmw5r {
  fill: currentColor;
  d: path("M22 2H2v20h20zm-3 16.5h-2v-2H7v2H5v-7.31L6.89 5.5H17.1l1.9 5.69z");
}

.po6vlitvx {
  cx: 9px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.s6zu9-z9k {
  fill: currentColor;
  d: path("m8.33 7.5l-.66 2h8.66l-.66-2z");
}

</style>
