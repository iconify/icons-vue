<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r5x2o3bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vibrons" /></template>
<style>
.r5x2o3bck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 17.044v14.23m7.4 10.206V5.969m7.4 28.391V6.106m7.4 7.13v28.796m7.4-.397V6.292m7.4 5.564v21.29");
}

</style>
