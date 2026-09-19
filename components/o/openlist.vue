<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wyzyf7csa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openlist" /></template>
<style>
.wyzyf7csa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.796 16.649A21.5 21.5 0 0 1 24 2.5c11.874 0 21.5 9.626 21.5 21.5S35.874 45.5 24 45.5a21.5 21.5 0 0 1-4.995-.588l11.267-17.007M7.026 37.196L19.585 18.25");
}

</style>
