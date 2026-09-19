<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lefv39bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:twitter-alt-2" /></template>
<style>
.lefv39bck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 41.5h-7.368L6.5 6.5h7.368l27.632 35zM21.941 26.059L6.5 41.5m35-35L26.059 21.941");
}

</style>
