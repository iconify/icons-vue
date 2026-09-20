<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7wf1wbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-24-regular" /></template>
<style>
.n7wf1wbcv {
  fill: currentColor;
  d: path("M20.5 12a8.5 8.5 0 1 0-17 0a8.5 8.5 0 0 0 17 0m1.5 0c0 5.523-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2s10 4.477 10 10M7 13.25a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m5 0a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5m5 0a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

</style>
