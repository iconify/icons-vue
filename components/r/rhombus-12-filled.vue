<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jqf-ye_eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rhombus-12-filled" /></template>
<style>
.jqf-ye_eb {
  fill: currentColor;
  d: path("M9.667 2a1.333 1.333 0 0 1 1.23 1.846l-2.18 5.231A1.5 1.5 0 0 1 7.334 10h-5a1.333 1.333 0 0 1-1.23-1.846l2.18-5.231A1.5 1.5 0 0 1 4.666 2z");
}

</style>
