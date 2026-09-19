<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xfkvxob0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reev-pro" /></template>
<style>
.xfkvxob0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 33.25v9.25h33L28.3 24h2.95a9.25 9.25 0 0 0 0-18.5H7.5v9.25M16.75 24H7.5");
}

</style>
