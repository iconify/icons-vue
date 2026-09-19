<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e8ct6s_va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:video" /></template>
<style>
.e8ct6s_va {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 9v30m-5.74-26.96h5.74m-5.74 5.98h5.74M37.76 24h5.74m-5.74 5.98h5.74m-5.74 5.98h5.74M10.24 12.04h27.53v23.91H10.24zM4.5 39V9m5.74 30V9m27.52 30V9M10.24 35.96H4.5m5.74-5.98H4.5M10.24 24H4.5m5.74-5.98H4.5m5.74-5.98H4.5");
}

</style>
