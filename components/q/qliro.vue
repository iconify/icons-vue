<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jumkp8bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qliro" /></template>
<style>
.jumkp8bss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.495 31.248H35.5a9 9 0 1 0 0-18h-23a9 9 0 1 0 0 18h8.176c.848 0 1.66.337 2.26.936l2.569 2.568");
}

</style>
