<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="feosc6bul"/><path class="fhlc4ccxe"/><path class="t5c3rngjx"/><path class="tka046-pz"/><path class="wp3k5kztn"/><path class="lguggybwl"/><g class="pc_dl159y"><ellipse class="nlt1vfbrr"/><ellipse class="o3vcj9pcl"/><path class="uzyzrsbuu"/></g><g class="vxz8xgbto"><ellipse class="mfnfs-bkb"/><ellipse class="c_x3-ub4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pig-face" /></template>
<style>
.c_x3-ub4y {
  cx: 48.4px;
  cy: 34.4px;
  rx: 3.1px;
  ry: 5.6px;
}

.feosc6bul {
  fill: var(--svg-color--fc97b2, #fc97b2);
  d: path("M20.6 14.8c-2.4-4.5-18.2-3.1-18.2-3.1s-1.9 16 2.7 18.5c3.5 1.9 17.4-11.8 15.5-15.4");
}

.fhlc4ccxe {
  fill: var(--svg-color--ffd7e4, #ffd7e4);
  d: path("M17.6 17.2c-1.5-2.8-11.3-1.9-11.3-1.9S5.2 25.3 8 26.8c2.2 1.2 10.8-7.3 9.6-9.6");
}

.lguggybwl {
  fill: var(--svg-color--ffd7e4, #ffd7e4);
  d: path("M46 49.8c0 8.1-6.3 7.2-14 7.2s-14 .9-14-7.2s6.3-12.1 14-12.1s14 4 14 12.1");
}

.mfnfs-bkb {
  cx: 15.6px;
  cy: 34.6px;
  rx: 3.1px;
  ry: 5.6px;
}

.nlt1vfbrr {
  cx: 25.7px;
  cy: 48px;
  rx: 3.4px;
  ry: 6.3px;
}

.o3vcj9pcl {
  cx: 38.3px;
  cy: 48px;
  rx: 3.4px;
  ry: 6.3px;
}

.pc_dl159y {
  fill: var(--svg-color--bf7b90, #bf7b90);
}

.t5c3rngjx {
  fill: var(--svg-color--fc97b2, #fc97b2);
  d: path("M58.7 30.1c4.5-2.4 3.1-18.1 3.1-18.1s-16.1-1.9-18.6 2.7C41.3 18.2 55 32 58.7 30.1");
}

.tka046-pz {
  fill: var(--svg-color--ffd7e4, #ffd7e4);
  d: path("M56.2 27.1c2.8-1.5 1.9-11.2 1.9-11.2s-10-1.2-11.6 1.7c-1.1 2.2 7.5 10.7 9.7 9.5");
}

.uzyzrsbuu {
  d: path("M32 22.6s-3-10-9.7-11.9c0 0 3-1.7 5.2-.9c0 0 .1-1.8-1.8-3.1c0 0 4.3-.9 6.5 2.1c0 0 .3-3.2-.5-4.8c0 0 7.1 1.7 9 7.8c0 0-7.3 2.1-8.7 10.8");
}

.vxz8xgbto {
  fill: var(--svg-color--493b30, #493b30);
}

.wp3k5kztn {
  fill: var(--svg-color--fc97b2, #fc97b2);
  d: path("M58.8 39.4C58.8 56.8 46.8 60 32 60S5.2 56.8 5.2 39.4S21.7 9.5 32 9.5S58.8 22 58.8 39.4");
}

</style>
