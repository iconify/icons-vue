<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4svjbdjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:substack-reader" /></template>
<style>
.y4svjbdjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.025 10.082V5.5H7.747v4.582zm0 8.268v-4.58H7.747v4.581zm.231 24.149V22.318c0-.164-.973-.108-1.887-.108H9.402c-.914 0-1.655-.055-1.655.108v19.888c.281-.163 15.341-8.212 16.169-8.598c.516.297 13.646 7.338 16.34 8.891");
}

</style>
