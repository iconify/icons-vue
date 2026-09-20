<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmq2a2b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-right-rotate-270-24-regular" /></template>
<style>
.qmq2a2b8x {
  fill: currentColor;
  d: path("M5.75 19a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v15.5a.75.75 0 0 1-.75.75m13-5a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v10.5a.75.75 0 0 1-.75.75m-7.25 7.25a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0z");
}

</style>
