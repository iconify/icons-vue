<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jz-pz72tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nomachine" /></template>
<style>
.jz-pz72tq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 39.376V8.624H13.562v30.752M27.96 8.624v30.752M5.5 8.624v23.611m0 4.146v2.995");
}

</style>
