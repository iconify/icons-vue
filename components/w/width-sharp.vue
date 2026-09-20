<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmlr_lb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:width-sharp" /></template>
<style>
.tmlr_lb3m {
  fill: currentColor;
  d: path("m7 16l-4-4l4-4l1.425 1.4l-1.6 1.6h10.35L15.6 9.4L17 8l4 4l-4 4l-1.4-1.4l1.575-1.6H6.825L8.4 14.6z");
}

</style>
