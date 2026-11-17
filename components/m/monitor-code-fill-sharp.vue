<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkkgbibka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-code-fill-sharp" /></template>
<style>
.zkkgbibka {
  fill: currentColor;
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm7.707 5.207a.999.999 0 1 0-1.414-1.414l-2 2a.997.997 0 0 0 0 1.414l2 2a.999.999 0 1 0 1.414-1.414L9.414 10.5Zm6 .586l-2-2a.999.999 0 1 0-1.414 1.414l1.293 1.293l-1.293 1.293a.999.999 0 1 0 1.414 1.414l2-2a1 1 0 0 0 0-1.414M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
