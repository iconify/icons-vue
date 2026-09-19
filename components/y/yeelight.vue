<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ulz77ubti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yeelight" /></template>
<style>
.ulz77ubti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.703 30.995L4.5 26.62V13.764L24 21.38v12.856m8.297-3.241L43.5 26.62V13.764L24 21.38v12.856");
}

</style>
