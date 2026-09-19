<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9o58u-lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wire-flow" /></template>
<style>
.c9o58u-lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 14.117l12.962 19.766m12.962-19.766l-4.041 6.163m-4.992 7.612l-3.93 5.991m.115-19.766l12.962 19.766M43.5 14.117L30.538 33.883");
}

</style>
