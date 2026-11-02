<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxqjxbbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:router-fill-sharp" /></template>
<style>
.qxqjxbbnd {
  fill: currentColor;
  d: path("M10.293 5.293a8.07 8.07 0 0 1 11.414 0a1.002 1.002 0 0 1-1.414 1.414a6 6 0 0 0-2.008-1.334A6 6 0 0 0 16 4.929a6.04 6.04 0 0 0-4.293 1.778a.999.999 0 1 1-1.414-1.414m3 3A3.82 3.82 0 0 1 16 7.172c.494-.001.983.094 1.44.28a3.8 3.8 0 0 1 1.267.841a.997.997 0 0 1 0 1.414a1 1 0 0 1-1.414 0A1.82 1.82 0 0 0 16 9.172a1.82 1.82 0 0 0-1.293.535a.999.999 0 1 1-1.414-1.414M17 12v2h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h12v-2a1 1 0 0 1 2 0");
}

</style>
