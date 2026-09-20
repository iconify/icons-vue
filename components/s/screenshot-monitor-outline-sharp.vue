<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgnw-h00f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screenshot-monitor-outline-sharp" /></template>
<style>
.qgnw-h00f {
  fill: currentColor;
  d: path("M15.5 15.692h3.192V12.5h-.884v2.308H15.5zM5.308 9.5h.884V7.192H8.5v-.884H5.308zM9 20v-2H3V4h18v14h-6v2zm-5-3h16V5H4zm0 0V5z");
}

</style>
