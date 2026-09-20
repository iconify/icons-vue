<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="l6gfs681a"/><path class="zanz5wbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:one-thirty" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.l6gfs681a {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M18 31a1 1 0 0 1-1-1V18a1 1 0 0 1 2 0v12a1 1 0 0 1-1 1");
}

.yqfvb1bwf {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.zanz5wbvr {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M17.999 19a1 1 0 0 1-.893-1.447l4-8a1.001 1.001 0 0 1 1.789.895l-4 8c-.176.35-.529.552-.896.552");
}

</style>
