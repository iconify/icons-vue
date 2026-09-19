<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cy9g6zl7n"/><path class="yymqw5bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:t-mobile" /></template>
<style>
.cy9g6zl7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.812 22.342h-7.786v7.786l.001.001h7.786v-7.786Zm-31.626 0h7.785v7.786l-.002.001H8.185v-7.786Z");
}

.yymqw5bcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.838 43.5v-3.147c-5.388-.29-6.316-2.284-6.395-5.267V7.72c4.94.503 9.812.37 9.812 10.658h2.56V4.5h-31.6v13.878h2.56c0-10.117 4.873-10.155 9.813-10.658v27.366c-.08 2.983-1.008 4.977-6.395 5.267V43.5Z");
}

</style>
