<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdq37jjij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-score" /></template>
<style>
.xdq37jjij {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5l4-4l4 4l6-6zm0-8.5l-6 6l-4-4l-4 4V5h14zM13.5 9V6H12v6h1.5zm3.7 3l-2-3l2-3h-1.7l-2 3l2 3zM11 10.5H8.5v-.75H11V6H7v1.5h2.5v.75H7V12h4z");
}

</style>
