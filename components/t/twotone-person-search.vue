<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il8-b_-wq"/><path class="rmcukm7fz"/><path class="arr8g5bzj"/><circle class="wi4da5bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-person-search" /></template>
<style>
.arr8g5bzj {
  fill: currentColor;
  d: path("M19.43 18.02c.36-.59.57-1.28.57-2.02c0-2.21-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4c.74 0 1.43-.22 2.02-.57L20.59 22L22 20.59c-1.5-1.5-.79-.8-2.57-2.57M16 18c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2s-.9 2-2 2");
}

.il8-b_-wq {
  fill: currentColor;
  d: path("M4 18c.22-.72 3.31-2 6-2c0-.7.13-1.37.35-1.99C7.62 13.91 2 15.27 2 18v2h9.54c-.52-.58-.93-1.25-1.19-2zm6-5c2.21 0 4-1.79 4-4s-1.79-4-4-4s-4 1.79-4 4s1.79 4 4 4m0-6a2 2 0 1 1 .001 3.999A2 2 0 0 1 10 7");
}

.rmcukm7fz {
  fill: currentColor;
  d: path("M10.35 18s-.35-.79-.35-2c-2.69 0-5.77 1.28-6 2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.wi4da5bgf {
  cx: 10px;
  cy: 9px;
  r: 2px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
