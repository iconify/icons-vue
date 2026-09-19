<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd93urbzo"/><path class="w8ri5cc6j"/><circle class="iu35e1xme"/><path class="zzmirg-xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-report" /></template>
<style>
.hd93urbzo {
  fill: currentColor;
  d: path("M9.1 5L5 9.1v5.8L9.1 19h5.8l4.1-4.1V9.1L14.9 5zM12 17c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m1-3h-2V7h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.iu35e1xme {
  cx: 12px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

.w8ri5cc6j {
  fill: currentColor;
  d: path("M15.73 3H8.27L3 8.27v7.46L8.27 21h7.46L21 15.73V8.27zM19 14.9L14.9 19H9.1L5 14.9V9.1L9.1 5h5.8L19 9.1z");
}

.zzmirg-xv {
  fill: currentColor;
  d: path("M11 7h2v7h-2z");
}

</style>
