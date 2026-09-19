<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g92vhsbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mytim" /></template>
<style>
.g92vhsbfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.685 10.627H43.5M4.5 24h14.635M4.5 37.373h14.635M28.434 24h14.635M28.434 37.373h14.635");
}

</style>
