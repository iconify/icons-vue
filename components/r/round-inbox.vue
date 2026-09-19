<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qibk2g00h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-inbox" /></template>
<style>
.qibk2g00h {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 2v9h-3.56c-.36 0-.68.19-.86.5c-.52.9-1.47 1.5-2.58 1.5s-2.06-.6-2.58-1.5a1 1 0 0 0-.86-.5H5V5z");
}

</style>
