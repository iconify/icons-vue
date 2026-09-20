<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGeucSEevY" class="xgoz1f1gg"/></defs><path class="uw-5w_bdv"/><ellipse class="a5h9y6ghe"/><use href="#SVGeucSEevY"/><use href="#SVGeucSEevY"/><path class="ckrgiobiu"/><g class="pl9mke6sb"><path class="i2nz58blv"/></g><path class="sv56t6hnd"/><ellipse class="ffokp0_ac"/><path class="fa54qfniy"/><ellipse class="kzrd_9nby"/><ellipse class="p23lv0byi"/><ellipse class="vcqgmsbzx"/><path class="v02rkbbdi"/><ellipse class="ryge3tb7c"/><path class="i-we9pbtu"/><ellipse class="kk-e5bbnc"/><ellipse class="ydgyl4-4x"/><ellipse class="mkn_tnb_x"/><path class="en58axs3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:scroll" /></template>
<style>
.a5h9y6ghe {
  cx: 114.59px;
  cy: 108.83px;
  fill: var(--svg-color--f2bd72, #f2bd72);
  rx: 9.41px;
  ry: 12.65px;
}

.ckrgiobiu {
  fill: var(--svg-color--f2bd72, #f2bd72);
  d: path("m32.26 100.75l.09-9.1s59.53 6.46 77.04-14.12v22.99z");
}

.en58axs3a {
  fill: var(--svg-color--ba793e, #ba793e);
  d: path("M16.62 16.7c1.27.39 2.82 3.08.18 5.66c-.67.65.02 2.09.48 3.3c.58 1.54 1 2.37 2.34 1.45c1.8-1.22 3.51-4.71 3.51-7.67c0-4.79-2.71-8.68-6.05-8.68c-1.72 0-3.06.55-4.19 2.88c-.5 1.04-.55 2.37 1.04 2.53c0 .01 1.79.25 2.69.53");
}

.fa54qfniy {
  fill: var(--svg-color--784d30, #784d30);
  d: path("M45.71 108.17c0 5.33-3.34 8.35-6.92 9.33c-4.61 1.26-6.53.16-6.53.16V98.68s3.25-.82 6.72.16c3.54.99 6.73 4 6.73 9.33");
}

.ffokp0_ac {
  cx: 38.73px;
  cy: 108.83px;
  fill: var(--svg-color--f2bd72, #f2bd72);
  rx: 9.41px;
  ry: 12.65px;
}

.i-we9pbtu {
  fill: var(--svg-color--784d30, #784d30);
  d: path("M29.32 19.43c0 5.33-3.34 8.35-6.92 9.33c-4.61 1.26-6.53.16-6.53.16V9.94s3.25-.82 6.72.16c3.53.98 6.73 4 6.73 9.33");
}

.i2nz58blv {
  d: path("M45.52 30.1c1.17 0 2.35-.02 3.52 0c.89.02 1.72.14 2.63.05c.98-.1 1.96-.29 2.96-.26c1.22.04 2.39.41 3.62.41c.6 0 1.14-.17 1.73-.2c.68-.03 1.36 0 2.04 0h4.3m12.69 0c.73 0 1.49.06 2.21-.05c1.12-.17 2.19-.63 3.36-.53c1.25.11 2.31.84 3.54 1.03c1.99.29 3.86-.9 5.87-1.09c.64-.06 1.28-.02 1.92.03c1.45.12 2.88.3 4.31.53m-54.7 23.49c1 0 2.04.1 3.03 0c1.39-.14 2.73-.63 4.16-.56c1.44.07 2.76.7 4.17.95c1.94.33 3.89-.08 5.81-.33c2.05-.27 4-.05 6.06-.05h7.7m10.32-.01c.74 0 1.48-.01 2.22 0c1.25.02 2.18-.38 3.37-.61c1.69-.33 3.38.19 5.05.36c1.23.12 2.52.26 3.75.25m-32.6 23.45c1.34 0 2.74-.09 4.05.09c2.27.32 4.18-.39 6.41-.62c2.09-.22 4.18.2 6.28.37c2.18.18 4.37.1 6.56.02c2.27-.08 4.54.13 6.83.13m-54.11.01c1.96 0 3.89.37 5.85.23c.66-.05 1.32-.14 1.99-.17c1.33-.07 2.67.23 3.98.08c.87-.1 1.7-.14 2.58-.14m9.58-58.48c1.34 0 2.74-.09 4.05.09c2.27.32 4.18-.39 6.41-.62c2.09-.22 4.18.2 6.28.37c2.18.18 4.37.1 6.56.02c2.27-.08 4.54.13 6.83.13m-54.11.01c1.96 0 3.89.37 5.85.23c.66-.05 1.32-.14 1.99-.17c1.33-.07 2.67.23 3.98.08c.87-.1 1.7-.14 2.58-.14M45.52 41.87c.96 0 1.89.04 2.83.11c1.68.12 3.24-.64 4.87-.81c2.05-.21 4.07.45 6.1.75c2.01.3 4.05.12 6.07 0c.92-.06 1.88-.14 2.8-.12c.99.02 1.93.33 2.92.32c1.27-.01 2.44-.57 3.69-.76c2.78-.43 5.55.97 8.36.78c.92-.06 1.81-.29 2.72-.38c1.12-.11 2.25-.01 3.37.09l4.98.45M45.52 65.26c.96 0 1.89.04 2.83.11c1.68.12 3.24-.64 4.87-.81c2.05-.21 4.07.45 6.1.75c2.01.3 4.05.12 6.07 0c.92-.06 1.88-.14 2.8-.12c.99.02 1.93.33 2.92.32c1.27-.01 2.44-.57 3.69-.76c2.78-.43 5.55.97 8.36.78c.92-.06 1.81-.29 2.72-.38c1.12-.11 2.25-.01 3.37.09l4.98.45M58.39 88.62c.52.01.99-.11 1.5-.13c.74-.04 1.47.17 2.2.28c1.75.26 3.58.39 5.32.01c.98-.22 1.91-.59 2.91-.73c2.51-.36 4.99.76 7.54.75c2.2-.02 4.56-1.02 6.73-.44c1.42.37 2.88.28 4.38.28");
  opacity: var(--svg-opacity--0-77, 0.77);
}

.kk-e5bbnc {
  cx: 17.09px;
  cy: 19.43px;
  fill: var(--svg-color--784d30, #784d30);
  rx: 6.72px;
  ry: 9.65px;
}

.kzrd_9nby {
  cx: 33.48px;
  cy: 108.17px;
  fill: var(--svg-color--784d30, #784d30);
  rx: 6.72px;
  ry: 9.65px;
}

.mkn_tnb_x {
  cx: 8.46px;
  cy: 19.44px;
  fill: var(--svg-color--ba793e, #ba793e);
  rx: 4.46px;
  ry: 4.5px;
}

.p23lv0byi {
  cx: 33.48px;
  cy: 108.18px;
  fill: var(--svg-color--784d30, #784d30);
  rx: 6.72px;
  ry: 9.65px;
}

.pl9mke6sb {
  fill: none;
  stroke: var(--svg-color--9e673c, #9e673c);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3-005px, 3.005px);
  opacity: var(--svg-opacity--0-6, 0.6);
}

.ryge3tb7c {
  cx: 22.34px;
  cy: 20.09px;
  fill: var(--svg-color--f2bd72, #f2bd72);
  rx: 10.09px;
  ry: 13.57px;
}

.sv56t6hnd {
  fill: var(--svg-color--fcebcd, #fcebcd);
  d: path("M38.25 96.18v6.17h84.41c-1.64-3.69-4.64-6.17-8.07-6.17z");
}

.uw-5w_bdv {
  fill: var(--svg-color--d68b52, #d68b52);
  d: path("M22.13 18.65h23.19v15.08H22.13z");
}

.v02rkbbdi {
  fill: var(--svg-color--ba793e, #ba793e);
  d: path("M33.02 105.44c1.27.39 2.82 3.08.18 5.66c-.67.65.02 2.09.48 3.3c.58 1.54 1 2.37 2.34 1.45c1.8-1.22 3.51-4.71 3.51-7.67c0-4.79-2.71-8.68-6.05-8.68c-1.72 0-3.06.55-4.19 2.88c-.5 1.04-.55 2.37 1.04 2.53c0 .01 1.78.26 2.69.53");
}

.vcqgmsbzx {
  cx: 24.86px;
  cy: 108.18px;
  fill: var(--svg-color--ba793e, #ba793e);
  rx: 4.46px;
  ry: 4.5px;
}

.xgoz1f1gg {
  fill: var(--svg-color--ffd8a1, #ffd8a1);
  d: path("M114.59 96.18h-5.18s.04-63.41.04-74.11s-7.61-15.55-10.42-15.55h-76.9s10.1 1.21 10.23 15.55c.09 10.21 0 62.8 0 79.61s6.37 19.79 6.37 19.79h75.38c.07 0 .14-.01.21-.02c.09 0 .18.02.27.02c5.2 0 9.41-5.66 9.41-12.65c0-6.97-4.21-12.64-9.41-12.64");
}

.ydgyl4-4x {
  cx: 17.09px;
  cy: 19.44px;
  fill: var(--svg-color--784d30, #784d30);
  rx: 6.72px;
  ry: 9.65px;
}

</style>
