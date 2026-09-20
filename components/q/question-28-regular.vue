<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xjz94sb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:question-28-regular" /></template>
<style>
.xjz94sb1w {
  fill: currentColor;
  d: path("M14 4a6 6 0 0 0-6 6a.75.75 0 0 0 1.5 0a4.5 4.5 0 1 1 9 0c0 1.383-.3 2.233-.697 2.839c-.412.627-.964 1.055-1.633 1.564l-.033.026c-.637.485-1.38 1.052-1.944 1.91c-.587.894-.943 2.044-.943 3.661v.25a.75.75 0 0 0 1.5 0V20c0-1.383.3-2.233.697-2.838c.412-.628.964-1.056 1.633-1.565l.033-.026c.637-.485 1.38-1.052 1.944-1.91c.587-.894.943-2.044.943-3.661a6 6 0 0 0-6-6m0 21a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
