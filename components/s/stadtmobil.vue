<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zh9i-kbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stadtmobil" /></template>
<style>
.zh9i-kbmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40 24L8 5.5A37.14 37.14 0 0 1 12.93 24A37.14 37.14 0 0 1 8 42.5Z");
}

</style>
