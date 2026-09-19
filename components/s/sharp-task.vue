<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3wr5eb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-task" /></template>
<style>
.j3wr5eb7w {
  fill: currentColor;
  d: path("M14 2H4v20h16V8zm-3.06 16L7.4 14.46l1.41-1.41l2.12 2.12l4.24-4.24l1.41 1.41zM13 9V3.5L18.5 9z");
}

</style>
