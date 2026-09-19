<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg17xbcfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-delete-outline" /></template>
<style>
.zg17xbcfe {
  fill: currentColor;
  d: path("M6 21h12V7H6zM8 9h8v10H8zm7.5-5l-1-1h-5l-1 1H5v2h14V4z");
}

</style>
