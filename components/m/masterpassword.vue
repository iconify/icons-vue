<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w8a8facgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:masterpassword" /></template>
<style>
.w8a8facgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.94 19.56A4.44 4.44 0 1 1 4.5 24a4.44 4.44 0 0 1 4.44-4.44m12.37 0A4.44 4.44 0 1 1 16.87 24a4.44 4.44 0 0 1 4.44-4.44m12.37 0A4.44 4.44 0 1 1 29.24 24a4.44 4.44 0 0 1 4.44-4.44m9.82-7.09v23.06");
}

</style>
