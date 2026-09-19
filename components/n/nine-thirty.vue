<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="s6obg5r9c"/><path class="bz5ykio_b"/><path class="z6-ug4b2n"/><path class="h9s8-vidm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:nine-thirty" /></template>
<style>
.bz5ykio_b {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 31.801C0 49.335 14.265 63.6 31.799 63.6S63.6 49.335 63.6 31.801C63.6 14.265 49.333 0 31.799 0S0 14.265 0 31.801m6.191 0c0-14.122 11.488-25.61 25.608-25.61s25.61 11.488 25.61 25.61S45.92 57.41 31.799 57.41S6.191 45.922 6.191 31.801");
}

.h9s8-vidm {
  fill: var(--svg-color--788288, #788288);
  d: path("M15.942 28.929c-1.429 0-2.589.842-2.589 1.879c0 1.035 1.161 1.877 2.591 1.877l15.16.006c1.426 0 2.587-.844 2.585-1.879c.002-1.037-1.159-1.879-2.583-1.881l-15.166-.002");
}

.s6obg5r9c {
  cx: 31.801px;
  cy: 31.799px;
  r: 29.458px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.z6-ug4b2n {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M29.933 52.629c0 1.432.842 2.588 1.879 2.588s1.879-1.156 1.879-2.588V31.678c0-1.432-.846-2.589-1.879-2.589c-1.037 0-1.879 1.157-1.879 2.589z");
}

</style>
