<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="hqprekeij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-28-regular" /></template>
<style>
.hqprekeij {
  fill: currentColor;
  d: path("M2.75 12.998a.75.75 0 0 0 0 1.5h22.5a.75.75 0 0 0 0-1.5zM24 4.75A2.75 2.75 0 0 0 21.25 2H6.75A2.75 2.75 0 0 0 4 4.75v7.248h1.5V4.75c0-.691.56-1.25 1.25-1.25h14.5c.69 0 1.25.559 1.25 1.25v7.247H24zm-18.5 18v-7.252H4v7.252a2.75 2.75 0 0 0 2.75 2.75h14.5A2.75 2.75 0 0 0 24 22.75v-7.252h-1.5v7.252c0 .69-.56 1.25-1.25 1.25H6.75c-.69 0-1.25-.56-1.25-1.25");
}

</style>
