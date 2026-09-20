<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l03g4x2ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:transparency-square-16-regular" /></template>
<style>
.l03g4x2ti {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm-7 1A1.5 1.5 0 0 0 3 4.5v1h2.5V8H3v2.5h2.5V13H8v-2.5h2.5V13h1a1.5 1.5 0 0 0 1.5-1.5v-1h-2.5V8H13V5.5h-2.5V3H8v2.5H5.5V3zM8 10.5H5.5V8H8zM10.5 8H8V5.5h2.5z");
}

</style>
