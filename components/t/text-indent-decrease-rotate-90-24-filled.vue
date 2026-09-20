<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geklnqwzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-rotate-90-24-filled" /></template>
<style>
.geklnqwzz {
  fill: currentColor;
  d: path("M8 9v8.5a1 1 0 0 1-1.993.117L6 17.5V9a1 1 0 0 1 1.993-.117zm4.707-6.707l2 2a1 1 0 0 1-1.32 1.497l-.094-.083L12 4.414l-1.293 1.293a1 1 0 0 1-1.497-1.32l.083-.094l2-2a1 1 0 0 1 1.32-.083zM13 9l.001 11.5a1 1 0 0 1-1.993.117L11 20.5V9a1 1 0 0 1 1.993-.117zm5 0v8.5a1 1 0 0 1-1.993.117L16 17.5V9a1 1 0 0 1 1.993-.117z");
}

</style>
