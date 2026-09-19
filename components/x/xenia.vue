<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hljqs0mlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xenia" /></template>
<style>
.hljqs0mlf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 39.93a167 167 0 0 1 37 0M5.5 8.07a167 167 0 0 0 37 0M14.75 39.16V8.84m18.5.134v30.062");
}

</style>
