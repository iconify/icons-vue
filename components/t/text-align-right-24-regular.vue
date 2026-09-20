<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqj_3wbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-24-regular" /></template>
<style>
.vqj_3wbud {
  fill: currentColor;
  d: path("M5 5.75A.75.75 0 0 1 5.75 5h15.5a.75.75 0 0 1 0 1.5H5.75A.75.75 0 0 1 5 5.75m5 13a.75.75 0 0 1 .75-.75h10.5a.75.75 0 0 1 0 1.5h-10.5a.75.75 0 0 1-.75-.75M2.75 11.5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5z");
}

</style>
