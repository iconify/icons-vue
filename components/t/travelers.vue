<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ar0fscbgm"/><path class="vkj7lzbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:travelers" /></template>
<style>
.ar0fscbgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.873c-12.514 0-17.428 9.694-18.5 12.33c3.845-2.559 8.543-2.426 12.062 0c3.845-2.559 9.357-2.426 12.876 0c3.52-2.426 8.217-2.559 12.062 0c-1.072-2.636-5.986-12.33-18.5-12.33");
}

.vkj7lzbzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.455 37.224a2.904 2.904 0 0 0 5.808 0V18.336");
}

</style>
