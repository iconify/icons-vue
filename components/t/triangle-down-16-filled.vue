<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jbt4tzb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-down-16-filled" /></template>
<style>
.jbt4tzb0d {
  fill: currentColor;
  d: path("M9.312 14.223a1.5 1.5 0 0 1-2.629 0l-5.5-10a1.5 1.5 0 0 1 1.315-2.222h10.999a1.5 1.5 0 0 1 1.314 2.223z");
}

</style>
