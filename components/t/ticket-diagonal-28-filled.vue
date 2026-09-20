<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kpzus4l_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ticket-diagonal-28-filled" /></template>
<style>
.kpzus4l_u {
  fill: currentColor;
  d: path("M14.542 2.805a2.75 2.75 0 0 1 3.889 0l1.17 1.17c.405.406.363 1.015.042 1.386a2.126 2.126 0 0 0 2.85 3.111l.217-.173c.35-.25.86-.279 1.236.027l.078.072l1.17 1.17l.19.21a2.75 2.75 0 0 1-.19 3.68l-2.837 2.837l-1.59-1.589a.75.75 0 0 0-1.06 1.06l1.59 1.59l-7.84 7.839a2.75 2.75 0 0 1-3.68.188l-.208-.188l-1.171-1.171a1.02 1.02 0 0 1-.042-1.386a2.1 2.1 0 0 0 .518-1.388a2.125 2.125 0 0 0-3.513-1.607c-.371.321-.98.363-1.386-.042l-1.17-1.17a2.75 2.75 0 0 1 0-3.889l7.839-7.839l1.589 1.59a.75.75 0 0 0 1.06-1.061l-1.589-1.59zm1.226 6.901a.75.75 0 0 0-1.06 1.06l2.525 2.526a.75.75 0 0 0 1.06-1.06z");
}

</style>
