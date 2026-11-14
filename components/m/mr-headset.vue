<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9etu1bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mr-headset" /></template>
<style>
.t9etu1bya {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 4.5h-6.5q-2.485 0-4.243 1.757Q2.75 8.015 2.75 10.5q0 1.894 1.02 3.365q-2.52.811-2.52 2.385q0 3.25 10.75 3.25t10.75-3.25q0-1.574-2.52-2.385q1.02-1.471 1.02-3.365q0-2.485-1.757-4.243Q17.735 4.5 15.25 4.5m-9 5q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25T6.25 9.5m9.25-2.25q2.25 0 2.25 2.25t-2.25 2.25t-2.25-2.25t2.25-2.25");
}

</style>
