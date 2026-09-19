<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v9a4g_b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prisma3d" /></template>
<style>
.v9a4g_b9n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.253 29.999l17.023 9.828m-36.552.001L22.746 30M24 27.803V8.172m0 7.343L12.083 36.156h23.834z");
}

</style>
