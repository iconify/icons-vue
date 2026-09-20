<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="l6gfs681a"/><path class="jil1ec4ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:two-thirty" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.jil1ec4ur {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M18.001 19a1 1 0 0 1-.582-1.814l7-5a1 1 0 0 1 1.163 1.628l-7 4.999a1 1 0 0 1-.581.187");
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

</style>
