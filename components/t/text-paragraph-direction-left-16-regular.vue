<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f_g0gtf_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-paragraph-direction-left-16-regular" /></template>
<style>
.f_g0gtf_l {
  fill: currentColor;
  d: path("M9 3a2.5 2.5 0 0 0 0 5h1V3zm2 0v10.5a.5.5 0 0 1-1 0V9H9a3.5 3.5 0 1 1 0-7h4.5a.5.5 0 0 1 0 1H13v10.5a.5.5 0 0 1-1 0V3zM3.854 6.146a.5.5 0 0 1 0 .708L2.707 8l1.147 1.146a.5.5 0 1 1-.708.708l-1.5-1.5a.5.5 0 0 1 0-.708l1.5-1.5a.5.5 0 0 1 .708 0");
}

</style>
