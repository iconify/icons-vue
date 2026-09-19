<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="keor5ccba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mixplorer" /></template>
<style>
.keor5ccba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.38 12.26l7.83 6l7.84-6v16.67H4.38zm18.53 8.1h4.28v8.57h-4.28Zm7 2.17h13.32l-3.65 6.4l3.8 6.77H29.74l3.79-6.77l-3.64-6.4Z");
}

</style>
