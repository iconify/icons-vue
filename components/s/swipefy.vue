<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yejj0fbgj"/><path class="gqaprdb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:swipefy" /></template>
<style>
.gqaprdb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.533 9.972l9.752 2.428q5.901 1.155 4.219 6.127l-5.179 20.65q-1.132 4.38-5.815 2.987L19.7 39.618q-1.941-.43-3.894-1.736");
}

.yejj0fbgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.34 8.214l15.762-2.676a2.665 2.665 0 0 1 3.075 2.18l4.196 24.737a2.665 2.665 0 0 1-2.179 3.075l-15.761 2.675a2.665 2.665 0 0 1-3.064-2.18L6.16 11.29a2.665 2.665 0 0 1 2.18-3.075");
}

</style>
