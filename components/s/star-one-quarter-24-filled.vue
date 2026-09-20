<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mih5rfbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-one-quarter-24-filled" /></template>
<style>
.mih5rfbpb {
  fill: currentColor;
  d: path("M9 6.725L8.43 7.88l-5.273.766c-1.107.16-1.55 1.522-.748 2.303l3.815 3.719l-.9 5.25c-.15.871.54 1.579 1.325 1.582c.21.001.426-.048.635-.158L9 20.44z");
}

</style>
