<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cbupdhliu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wink-video" /></template>
<style>
.cbupdhliu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.644 24.001L7.931 13.288L18.644 2.575L40.069 24L18.644 45.425L7.931 34.712z");
}

</style>
