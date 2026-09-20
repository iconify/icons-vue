<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7un6_b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:straight-outline-sharp" /></template>
<style>
.r7un6_b_b {
  fill: currentColor;
  d: path("M11 21V6.825L9.4 8.4L8 7l4-4l4 4l-1.4 1.4L13 6.825V21z");
}

</style>
