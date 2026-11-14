<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m0_3p5box"/><path class="l3t3sgbig"/><path class="wyzf045xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-request-review" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3t3sgbig {
  d: path("M13 3.5L10.5 6L13 8.5m.75 9.5c1.5-2.25 2.75-3 4.25-3s2.75.75 4 3c-1.25 2.25-2.5 3-4 3s-2.75-.75-4.25-3");
}

.m0_3p5box {
  d: path("M3.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m0 14a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6 7.25v9.5m12-4.6V9q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277q-.057-.136-.126-.266q-.07-.13-.152-.253q-.081-.122-.175-.236t-.198-.218t-.218-.198t-.236-.175q-.123-.082-.253-.152t-.266-.126t-.277-.099t-.286-.071q-.144-.029-.291-.044T15 6h-4.5");
}

.wyzf045xu {
  fill: currentColor;
  d: path("M16.75 18a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
