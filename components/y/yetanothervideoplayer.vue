<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zsjo04b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yetanothervideoplayer" /></template>
<style>
.zsjo04b8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.75 7.11h-19.5L4.5 24l9.75 16.89h19.5L43.5 24ZM19.12 30.82V17.17l13.65 6.88Z");
}

</style>
