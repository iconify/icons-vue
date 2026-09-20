<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="k28vhm8rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-28-filled" /></template>
<style>
.k28vhm8rz {
  fill: currentColor;
  d: path("M2.004 7.75A3.75 3.75 0 0 1 5.754 4H22.25A3.75 3.75 0 0 1 26 7.75v12.5A3.75 3.75 0 0 1 22.25 24H5.755a3.75 3.75 0 0 1-3.75-3.75zM7.728 9A.73.73 0 0 0 7 9.728v.044c0 .402.326.728.728.728h5.544A.73.73 0 0 0 14 9.772v-.044A.73.73 0 0 0 13.272 9zM7 13.728v.044c0 .402.326.728.728.728h10.544a.73.73 0 0 0 .728-.728v-.044a.73.73 0 0 0-.728-.728H7.728a.73.73 0 0 0-.728.728M7.728 17a.73.73 0 0 0-.728.728v.044c0 .402.326.728.728.728h7.544a.73.73 0 0 0 .728-.728v-.044a.73.73 0 0 0-.728-.728z");
}

</style>
