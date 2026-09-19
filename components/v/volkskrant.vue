<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zc209lbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volkskrant" /></template>
<style>
.zc209lbcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.431 5.5l-15.417 37l-15.417-37m19.594 26.976L16.951 5.5m18.882 0H42m-37 0h15.548");
}

</style>
