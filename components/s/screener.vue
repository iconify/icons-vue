<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lj49oqsiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screener" /></template>
<style>
.lj49oqsiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.511 24.493v11.173h11.137M35.677 16.6V5.5H24.541m-7.893 0H5.51v11.1m36.979 19.066h-6.812V42.5m-6.811-6.834h6.811V28.83");
}

</style>
