<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2mq-n2xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-fill-round" /></template>
<style>
.r2mq-n2xz {
  fill: currentColor;
  d: path("M22 16a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5ZM4 16a3.004 3.004 0 0 0 3 3h10a3 3 0 0 0 3-3V9H4Z");
}

</style>
