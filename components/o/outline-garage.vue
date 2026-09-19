<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-udmo56r"/><circle class="po6vlitvx"/><circle class="alqc54g4m"/><path class="y1tddabod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-garage" /></template>
<style>
.alqc54g4m {
  cx: 15px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.po6vlitvx {
  cx: 9px;
  cy: 13px;
  r: 1px;
  fill: currentColor;
}

.q-udmo56r {
  fill: currentColor;
  d: path("M20 2H4c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2m0 18H4V4h16z");
}

.y1tddabod {
  fill: currentColor;
  d: path("M5.78 18.5h.44c.43 0 .78-.36.78-.81V16.5h10v1.19c0 .45.34.81.78.81h.44c.43 0 .78-.36.78-.81v-6.5c-.82-2.46-1.34-4.03-1.56-4.69c-.05-.16-.12-.29-.19-.4c-.02-.02-.03-.04-.05-.07c-.38-.52-.92-.53-.92-.53H7.72s-.54.01-.92.54c-.02.02-.03.04-.05.06c-.07.11-.14.24-.19.4c-.22.66-.74 2.22-1.56 4.69v6.5c0 .45.35.81.78.81m2.55-11h7.34l.23.69l.43 1.31H7.67zM7 11.51v-.01h10v3H7z");
}

</style>
