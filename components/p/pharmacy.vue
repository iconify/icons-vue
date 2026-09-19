<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lr7abfbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pharmacy" /></template>
<style>
.lr7abfbtx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.319 17.744h-12.25V5.494h-12.5v12.25H5.319v12.5h12.25v12.25h12.5v-12.25h12.25z");
}

</style>
