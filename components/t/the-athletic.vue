<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t4-mxybon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:the-athletic" /></template>
<style>
.t4-mxybon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.3 6.5h12l12.7 35m4.5 0h-12m-15 0h-12M34 29H14m6.3-18.5L9 41.5");
}

</style>
