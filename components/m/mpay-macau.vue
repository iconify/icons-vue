<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nuoahgbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mpay-macau" /></template>
<style>
.nuoahgbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.787 42.5h10.354l5.914-36.362H11.7zm20.079-37l-4.238 26.039M31.845 5.582L27.326 33.36M37.391 8.256L33.444 32.59m8.769-17.153L40.287 27.3");
}

</style>
