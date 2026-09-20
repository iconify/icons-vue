<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cw-g_6iyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:xbox-console-20-regular" /></template>
<style>
.cw-g_6iyh {
  fill: currentColor;
  d: path("M7.5 6.5a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M4 2.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5zm4 7V17h7V3H5v14h2V9.5a.5.5 0 0 1 1 0");
}

</style>
