<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="d66bynbsp"/><path class="z_te80x9u"/><g class="ed4r-5bxj"><circle class="l1wvpc2td"/><path class="qdj3awbvw"/><circle class="q9qow-bys"/><circle class="a5tmf-bsp"/><circle class="iue8gmutx"/><circle class="t5f0a5stj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:waxing-crescent-moon" /></template>
<style>
.a5tmf-bsp {
  cx: 6.27px;
  cy: 18.892px;
  r: 2.192px;
}

.d66bynbsp {
  cx: 31.923px;
  cy: 32.08px;
  r: 31.832px;
  fill: var(--svg-color--405866, #405866);
}

.ed4r-5bxj {
  fill: var(--svg-color--4f6977, #4f6977);
}

.iue8gmutx {
  cx: 17.476px;
  cy: 19.63px;
  r: 3.428px;
}

.l1wvpc2td {
  cx: 29.24px;
  cy: 52.953px;
  r: 9.213px;
}

.q9qow-bys {
  cx: 5.924px;
  cy: 36.49px;
  r: 3.84px;
}

.qdj3awbvw {
  d: path("M41.813 24.454a3.915 3.915 0 0 1-3.916 3.912a3.912 3.912 0 0 1 0-7.823a3.914 3.914 0 0 1 3.916 3.911");
}

.t5f0a5stj {
  cx: 42.804px;
  cy: 11.06px;
  r: 4.828px;
}

.z_te80x9u {
  fill: var(--svg-color--f5eb35, #f5eb35);
  d: path("M45.805 3.395c10.7 5.131 18.1 16.03 18.1 28.687c0 14.483-9.68 26.685-22.916 30.542c10.952-10.531 19.08-39.11 4.811-59.23");
}

</style>
