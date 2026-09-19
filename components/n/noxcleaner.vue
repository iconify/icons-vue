<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mm63x5q5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noxcleaner" /></template>
<style>
.mm63x5q5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.532 42.5v-.002a32 32 0 0 1-1.015-7.978V23.803a3.67 3.67 0 0 0-3.672-3.672h-7.242V9.307c0-1.951-1.461-3.7-3.41-3.802a3.604 3.604 0 0 0-3.796 3.598v11.028h-7.242a3.67 3.67 0 0 0-3.672 3.672V34.52a32 32 0 0 1-1.015 7.98h31.063Zm-1.015-13.516H9.483M24 42.5v-3.097M34.145 42.5v-3.097M13.855 42.5v-3.097");
}

</style>
