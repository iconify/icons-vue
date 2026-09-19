<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mp61lukuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sharik" /></template>
<style>
.mp61lukuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.56 33.25A18 18 0 0 1 33.27 8.57c-5.4 16.04-5.99 18.08-24.71 24.68m32.62-14.63c4.22 15.2-9.77 26.76-22.57 22.56C27 27.67 30 25.92 41.18 18.62");
}

</style>
