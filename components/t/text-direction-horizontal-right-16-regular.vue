<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="twqrzow2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-horizontal-right-16-regular" /></template>
<style>
.twqrzow2g {
  fill: currentColor;
  d: path("M11.147 9.147a.5.5 0 0 1 .707 0l2 2a.5.5 0 0 1 0 .707l-2 2a.5.5 0 0 1-.707-.707L12.293 12H2.5a.5.5 0 0 1 0-1h9.793l-1.146-1.146a.5.5 0 0 1 0-.707M5 2a.5.5 0 0 1 .467.32l2.5 6.5a.5.5 0 0 1-.934.36L6.195 7h-2.39l-.838 2.18a.5.5 0 0 1-.934-.36l2.5-6.5l.033-.069A.5.5 0 0 1 5 2m6.147 1.146a.5.5 0 0 1 .707 0l2 2a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.707-.707L12.293 6H8.5a.5.5 0 0 1 0-1h3.793l-1.146-1.146a.5.5 0 0 1 0-.708M4.188 6H5.81L5 3.893z");
}

</style>
