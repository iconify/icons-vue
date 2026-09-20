<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jc4jcb3ep"/><path class="zvl5z-y5w"/><circle class="st5vxbc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rss" /></template>
<style>
.jc4jcb3ep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.573A28.927 28.927 0 0 1 34.427 42.5H42.5a37 37 0 0 0-37-37Z");
}

.st5vxbc2t {
  cx: 10.246px;
  cy: 37.755px;
  r: 4.745px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zvl5z-y5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.718 42.5h-7.4A16.82 16.82 0 0 0 5.5 25.682v-7.4A24.22 24.22 0 0 1 29.718 42.5");
}

</style>
