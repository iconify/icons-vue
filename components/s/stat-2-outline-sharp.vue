<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd400ybwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-2-outline-sharp" /></template>
<style>
.bd400ybwz {
  fill: currentColor;
  d: path("M7.4 18.4L6 17l6-6l6 6l-1.4 1.4l-4.6-4.575zm0-6L6 11l6-6l6 6l-1.4 1.4L12 7.825z");
}

</style>
