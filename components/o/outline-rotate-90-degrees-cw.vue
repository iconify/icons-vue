<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_a0-f2vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-rotate-90-degrees-cw" /></template>
<style>
.l_a0-f2vb {
  fill: currentColor;
  d: path("M2 13a9 9 0 0 0 13.79 7.62l-1.46-1.46c-.99.53-2.13.84-3.33.84c-3.86 0-7-3.14-7-7s3.14-7 7-7h.17L9.59 7.59L11 9l4-4l-4-4l-1.42 1.41L11.17 4H11a9 9 0 0 0-9 9m9 0l6 6l6-6l-6-6zm6 3.17L13.83 13L17 9.83L20.17 13z");
}

</style>
