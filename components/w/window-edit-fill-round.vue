<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2jjjm8id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-edit-fill-round" /></template>
<style>
.t2jjjm8id {
  fill: currentColor;
  d: path("M22 8v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5M4 9v7a3.004 3.004 0 0 0 3 3h10a3 3 0 0 0 3-3V9Zm4 6c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 11 18H9a1 1 0 0 1-1-1Zm2.586 1l3-3l-.586-.586l-3 3V16Z");
}

</style>
