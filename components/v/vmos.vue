<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b0t_kxbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vmos" /></template>
<style>
.b0t_kxbuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 7.978L24 40.022m-2.314-4.007L37.874 7.978m-4.624 0L19.375 32.011L5.5 7.978h9.25L24 24");
}

</style>
