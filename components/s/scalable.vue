<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="erc10dbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scalable" /></template>
<style>
.erc10dbby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 9.41v12.41L26.18 5.5h12.41a3.91 3.91 0 0 1 3.91 3.91M21.82 42.5H9.41a3.91 3.91 0 0 1-3.91-3.91V26.18zm18.327-2.353za8.034 8.034 0 0 1-11.362 0L7.853 19.215A8.034 8.034 0 1 1 19.215 7.853l20.932 20.932a8.034 8.034 0 0 1 0 11.362");
}

</style>
