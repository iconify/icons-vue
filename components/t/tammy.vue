<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b38av5bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tammy" /></template>
<style>
.b38av5bht {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.822 25.65L25.65 44.819a2.33 2.33 0 0 1-3.302 0L3.18 25.651zm-41.643-3.3l19.17-19.168a2.33 2.33 0 0 1 3.302 0l19.17 19.167z");
}

</style>
