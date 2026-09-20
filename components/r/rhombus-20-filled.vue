<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cnvggubzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-20-filled" /></template>
<style>
.cnvggubzb {
  fill: currentColor;
  d: path("M4.89 4.296A2 2 0 0 1 6.76 3h10.237a2 2 0 0 1 1.872 2.704l-3.76 10A2 2 0 0 1 13.238 17H3.001a2 2 0 0 1-1.872-2.704z");
}

</style>
