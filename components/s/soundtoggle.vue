<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-r5_fkbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundtoggle" /></template>
<style>
.a-r5_fkbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.557 42.5L15.724 28.666H6.39v-9.332h9.333L29.557 5.5Zm3.85-8.591a10.086 10.086 0 0 0 0-19.818z");
}

</style>
