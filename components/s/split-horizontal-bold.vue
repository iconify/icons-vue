<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m-jsezbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:split-horizontal-bold" /></template>
<style>
.m-jsezbix {
  fill: currentColor;
  d: path("M116 48v160a12 12 0 0 1-24 0v-68H53l11.52 11.51a12 12 0 0 1-17 17l-32-32a12 12 0 0 1 0-17l32-32a12 12 0 1 1 17 17L53 116h39V48a12 12 0 0 1 24 0m124.49 71.51l-32-32a12 12 0 0 0-17 17L203 116h-39V48a12 12 0 0 0-24 0v160a12 12 0 0 0 24 0v-68h39l-11.52 11.51a12 12 0 0 0 17 17l32-32a12 12 0 0 0 .01-17");
}

</style>
