<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnkewkj1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-add-space-before-24-regular" /></template>
<style>
.qnkewkj1u {
  fill: currentColor;
  d: path("M9.47 6.28a.75.75 0 0 1 1.06-1.06L12 6.69l1.47-1.47a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0zM3 11.75a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75m0 6a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75");
}

</style>
