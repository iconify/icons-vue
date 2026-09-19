<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="epinpev5q"/><path class="jfd4yf9cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:removebg" /></template>
<style>
.epinpev5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.976 10.89l19.23 9.637l-19.23 9.698l-19.257-9.698z");
}

.jfd4yf9cp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.2 23.287L4.94 26.13c-.361.31-.779.916 0 1.282l19.035 9.7l18.95-9.421c.571-.28.836-1.2.224-1.617l-5.342-2.824");
}

</style>
