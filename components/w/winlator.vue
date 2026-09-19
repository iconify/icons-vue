<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="emn0gb08o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:winlator" /></template>
<style>
.emn0gb08o {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M5.5 5.5V35a7.5 7.5 0 0 0 7.5 7.5h29.5V13A7.5 7.5 0 0 0 35 5.5zm0 18.5h37M24 5.5v37");
}

</style>
