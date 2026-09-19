<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hklfj86qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reburger" /></template>
<style>
.hklfj86qr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 33.75h37v8.75h-37zm0-28.25h37v8.75h-37zm0 23.625c23.056 5.886 13.944-7.886 37-2v-8.25c-23.056-5.886-13.944 7.886-37 2z");
}

</style>
