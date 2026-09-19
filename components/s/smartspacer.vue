<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ewyf8w47p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smartspacer" /></template>
<style>
.ewyf8w47p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M18.77 21.095h20.92M18.77 32.716h20.92M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24Zm-33.703-2.905h3.487c.642 0 1.162-.52 1.162-1.163v-3.486c0-.642-.52-1.162-1.162-1.162h-3.487c-.642 0-1.162.52-1.162 1.162v3.486c0 .642.52 1.163 1.162 1.163Zm4.649 8.716a2.905 2.905 0 1 1-5.81 0a2.905 2.905 0 0 1 5.81 0Z");
}

</style>
