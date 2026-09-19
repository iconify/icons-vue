<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zljq6usgl"/><path class="hef8_-37v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simeji" /></template>
<style>
.hef8_-37v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.002 36.853c1.51 1.51 8.061 8.137 14.112 4.643c3.895-2.249 2.878-8.336-1.758-12.973");
}

.zljq6usgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.482 21.989c0 13.998 6.66 21.222 23.219 12.784c13.758-7.012 13.449-20.811-.02-26.93C16.213 1.723 6.482 7.99 6.482 21.99z");
}

</style>
