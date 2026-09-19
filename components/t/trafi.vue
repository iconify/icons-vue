<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h521bw1ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trafi" /></template>
<style>
.h521bw1ca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.102 12.054L42.5 24L32.102 35.946M18.476 10.421L23.457 24l-4.981 13.579M5.5 8.465v31.07");
}

</style>
