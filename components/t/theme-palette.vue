<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxkybdcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:theme-palette" /></template>
<style>
.jxkybdcvr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q4.256 0 7.263 3.171q2.987 3.15 2.987 7.579q0 1.76-1.245 3.005T18 16.75h-1q-1.499 0-2.066.362q-.523.415-.256 1.709l.057.282q.264 1.315-.506 2.225q-.78.922-2.229.922q-4.246 0-7.248-3.002T1.75 12t3.002-7.248T12 1.75");
}

</style>
