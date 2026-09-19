<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hkmfaqohc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:quranic" /></template>
<style>
.hkmfaqohc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.015 33.445v8.2L42.5 26.742V6.355L24 15.657L5.5 6.355v20.387l31.485 14.903v-8.2m-12.92-2.947V19.373");
}

</style>
