<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oe-_mwkeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spark" /></template>
<style>
.oe-_mwkeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.882 33.568L24 4.5m0 0l17.002 34.973l-13.12-5.905L24 43.5m0-39v39m-3.882-9.932L24 4.5m0 0L6.998 39.473l13.12-5.905L24 43.5");
}

</style>
