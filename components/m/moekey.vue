<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qa6lu_bln"/><path class="yne59-b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moekey" /></template>
<style>
.qa6lu_bln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.5 5.5c-5.523 0-10 4.477-10 10v27h11v-26c0-.554.446-1 1-1s1 .446 1 1v26h11v-26c0-.554.446-1 1-1s1 .446 1 1v26h11v-27c0-5.523-4.477-10-10-10a10 10 0 0 0-8.494 4.744A10 10 0 0 0 15.5 5.5");
}

.yne59-b-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 23c0-.554.446-1 1-1s1 .446 1 1m11 0c0-.554.446-1 1-1s1 .446 1 1m-15 16h-11m24 0h-11m24 0h-11");
}

</style>
