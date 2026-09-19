<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="khnw39btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:opencloud" /></template>
<style>
.khnw39btm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.501 34.547L24 43.5L8.499 34.547m0-21.094L24 4.5l15.501 8.953M15.56 19.124L24 24l8.44-4.876M24 24v9.75");
}

</style>
