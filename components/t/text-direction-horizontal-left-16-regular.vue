<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="etm_m3byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-horizontal-left-16-regular" /></template>
<style>
.etm_m3byj {
  fill: currentColor;
  d: path("M4.146 9.146a.5.5 0 1 1 .707.708L3.707 11H13.5a.5.5 0 0 1 0 1H3.707l1.146 1.146a.5.5 0 1 1-.707.707l-2-2a.5.5 0 0 1 0-.707zM11 2a.5.5 0 0 1 .467.32l2.5 6.5a.5.5 0 0 1-.934.36L12.195 7h-2.39l-.838 2.18a.5.5 0 0 1-.934-.36l2.5-6.5l.033-.069A.5.5 0 0 1 11 2M4.146 3.146a.5.5 0 1 1 .707.708L3.707 5H7.5a.5.5 0 0 1 0 1H3.707l1.146 1.146a.5.5 0 0 1-.707.708l-2-2a.5.5 0 0 1 0-.708zM10.19 6h1.621L11 3.893z");
}

</style>
