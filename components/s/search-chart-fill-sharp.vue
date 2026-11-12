<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp2iefylg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-chart-fill-sharp" /></template>
<style>
.jp2iefylg {
  fill: currentColor;
  d: path("m16.321 14.906l5.386 5.387a.999.999 0 1 1-1.414 1.414l-5.387-5.386A8.002 8.002 0 0 1 4.343 4.343a8 8 0 0 1 11.978 10.563M6.293 11.293a.999.999 0 1 0 1.414 1.414L9 11.414l1.293 1.293a1 1 0 0 0 1.601-.26l2-4a1 1 0 1 0-1.788-.894l-1.38 2.759l-1.019-1.019a1 1 0 0 0-1.414 0Z");
}

</style>
