<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oykvc8kgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vector-three-fill" /></template>
<style>
.oykvc8kgg {
  fill: currentColor;
  d: path("m237.66 141.66l-32 32A8 8 0 0 1 192 168v-24h-68.69l-40 40l18.35 18.34A8 8 0 0 1 96 216H48a8 8 0 0 1-8-8v-48a8 8 0 0 1 13.66-5.66L72 172.69l40-40V64H88a8 8 0 0 1-5.66-13.66l32-32a8 8 0 0 1 11.32 0l32 32A8 8 0 0 1 152 64h-24v64h64v-24a8 8 0 0 1 13.66-5.66l32 32a8 8 0 0 1 0 11.32");
}

</style>
