<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4nskgbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-duo" /></template>
<style>
.j4nskgbqq {
  fill: currentColor;
  d: path("M20 2h-8C6.38 2 2 6.66 2 12.28C2 17.5 6.49 22 11.72 22C17.39 22 22 17.62 22 12V4c0-1.1-.9-2-2-2m-3 13l-3-2v2H7V9h7v2l3-2z");
}

</style>
