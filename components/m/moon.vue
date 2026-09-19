<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x6g-nkbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moon" /></template>
<style>
.x6g-nkbxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.213 35.215C38.476 41.551 31.585 45.8 23.702 45.8C11.838 45.8 2.22 36.174 2.22 24.3S11.837 2.8 23.7 2.8c-9.647 19.619 6.773 33.218 18.512 32.415");
}

</style>
