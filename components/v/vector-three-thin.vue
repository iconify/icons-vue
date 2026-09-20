<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q7ob5ubfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vector-three-thin" /></template>
<style>
.q7ob5ubfk {
  fill: currentColor;
  d: path("m234.83 138.83l-32 32a4 4 0 0 1-5.66-5.66L222.34 140H121.66l-64 64H96a4 4 0 0 1 0 8H48a4 4 0 0 1-4-4v-48a4 4 0 0 1 8 0v38.34l64-64V33.66L90.83 58.83a4 4 0 0 1-5.66-5.66l32-32a4 4 0 0 1 5.66 0l32 32a4 4 0 0 1-5.66 5.66L124 33.66V132h98.34l-25.17-25.17a4 4 0 0 1 5.66-5.66l32 32a4 4 0 0 1 0 5.66");
}

</style>
