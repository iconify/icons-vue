<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e1tunobhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nextcloudtalk" /></template>
<style>
.e1tunobhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.6 21.6 0 0 0 2.5 24a21.47 21.47 0 0 0 32.65 18.35c2.64 1 8.56 4.16 10 2.82s-1.73-8-2.5-10.48A21.47 21.47 0 0 0 24 2.5m0 8.17A13.33 13.33 0 1 1 10.67 24A13.4 13.4 0 0 1 24 10.67");
}

</style>
