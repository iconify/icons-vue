<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hnu2clbep"/><path class="dw1no_bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naviki" /></template>
<style>
.dw1no_bus {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.166 9.613C8.238 19.227 32.663 22.788 43.5 22.801");
}

.hnu2clbep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.046c32.448 2.609 17.226 15.587 7.123 26.341");
}

</style>
