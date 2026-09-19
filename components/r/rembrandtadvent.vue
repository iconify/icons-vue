<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1y_0acgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rembrandtadvent" /></template>
<style>
.m1y_0acgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.9 5.5v37m7.4-37v37m7.4-37v37m7.4-37v37m7.4-29.6h-37m37 7.4h-37m37 7.4h-37m37 7.4h-37m29.6 7.4H5.5h0v-37h37v29.6");
}

</style>
