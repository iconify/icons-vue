<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xijq9nyap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obtainium" /></template>
<style>
.xijq9nyap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.862 41.676L43.5 11.618L31.232 6.324l-8.681 3.448l3.56 8.965l5.504-2.186l-3.778 12.471l-11.306-6.48l5.504-2.186l-3.56-8.965l-8.682 3.448L4.5 27.107z");
}

</style>
