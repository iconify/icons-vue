<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qhlfo_bnx"/><path clip-rule="evenodd" class="sm6vazb3l"/><path class="epjn3_i5s"/><path class="r2ye424nw"/><path class="jy6691p1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtrm" /></template>
<style>
.epjn3_i5s {
  fill: var(--svg-color--440090, #440090);
  d: path("M19.57 12a7.57 7.57 0 1 1-15.139 0a7.57 7.57 0 0 1 15.14 0");
}

.ft5dv1b6b {
  fill: none;
}

.jy6691p1d {
  fill: var(--svg-color--030007, #030007);
  d: path("M18.115 11.999a6.114 6.114 0 1 1-12.228 0a6.114 6.114 0 0 1 12.228 0");
}

.qhlfo_bnx {
  fill: var(--svg-color--f7df53, #f7df53);
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0");
}

.r2ye424nw {
  fill: var(--svg-color--2f0065, #2f0065);
  d: path("M18.877 12a6.876 6.876 0 1 1-13.753 0a6.876 6.876 0 0 1 13.753 0");
}

.sm6vazb3l {
  fill: var(--svg-color--8117c9, #8117c9);
  fill-rule: evenodd;
  d: path("M12 20.63a8.63 8.63 0 1 0 0-17.26a8.63 8.63 0 0 0 0 17.258m0 .37a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
