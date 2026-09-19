<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ax2x0lb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tsacdop" /></template>
<style>
.ax2x0lb7y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.46 15.683V40.04a3.46 3.46 0 0 1-6.92 0V15.683a3.46 3.46 0 1 1 6.92 0m8.534-3.769a7.34 7.34 0 1 1-5.07 13.777M12.006 18.73a7.34 7.34 0 1 1 5.07-13.777m-.001 0l18.919 6.96m-5.069 13.778L12.006 18.73");
}

</style>
