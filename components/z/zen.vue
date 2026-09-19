<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fi0cirdbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zen" /></template>
<style>
.fi0cirdbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5C24 18.457 29.653 24 44.5 24C29.568 24 24 29.657 24 44.5C24 29.59 18.457 24 3.5 24C18.457 24 24 18.373 24 3.5");
}

</style>
