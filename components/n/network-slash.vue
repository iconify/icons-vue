<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wj6-qijdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:network-slash" /></template>
<style>
.wj6-qijdw {
  fill: currentColor;
  d: path("M96 54V40a16 16 0 0 1 16-16h32a16 16 0 0 1 16 16v32a16 16 0 0 1-16 16h-16.39a8 8 0 0 1 0-16H144V40h-32v14a8 8 0 0 1-16 0m117.92 156.62a8 8 0 1 1-11.84 10.76L117.19 128H72v32h8a16 16 0 0 1 16 16v32a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16v-32a16 16 0 0 1 16-16h8v-32H24a8 8 0 0 1 0-16h78.64L42.08 45.38a8 8 0 1 1 11.84-10.76ZM80 176H48v32h32Zm152-64h-68a8 8 0 0 0 0 16h20v22.83a8 8 0 1 0 16 0V128h32a8 8 0 0 0 0-16");
}

</style>
