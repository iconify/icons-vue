<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrfkm2b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pen-size-4-outline" /></template>
<style>
.lrfkm2b7v {
  fill: currentColor;
  d: path("M5 16.5q0-1.05.725-1.775l9-9Q15.45 5 16.5 5t1.775.725T19 7.5t-.725 1.775l-9 9Q8.55 19 7.5 19t-1.775-.725T5 16.5");
}

</style>
