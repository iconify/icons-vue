<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_oc1kbka"/><path class="m8s6--oun"/><path class="dpptcnn_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-timer" /></template>
<style>
.dpptcnn_b {
  fill: currentColor;
  d: path("M11 8h2v6h-2z");
}

.m8s6--oun {
  fill: currentColor;
  d: path("M9 1h6v2H9zm10.03 6.39l1.42-1.42c-.43-.51-.9-.99-1.41-1.41l-1.42 1.42A8.96 8.96 0 0 0 12 4a9 9 0 0 0-9 9c0 4.97 4.02 9 9 9a8.994 8.994 0 0 0 7.03-14.61M12 20c-3.87 0-7-3.13-7-7s3.13-7 7-7s7 3.13 7 7s-3.13 7-7 7");
}

.r_oc1kbka {
  fill: currentColor;
  d: path("M12 6c-3.87 0-7 3.13-7 7s3.13 7 7 7s7-3.13 7-7s-3.13-7-7-7m1 8h-2V8h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
