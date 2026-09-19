<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhlbzlc6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-video-file" /></template>
<style>
.xhlbzlc6h {
  fill: currentColor;
  d: path("M14 2H4v20h16V8zm-1 7V3.5L18.5 9zm1 5l2-1.06v4.12L14 16v2H8v-6h6z");
}

</style>
