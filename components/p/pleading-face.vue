<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGH5as8dov" cx="64" cy="24" r="56.96" fx="64" fy="24" gradientTransform="matrix(1 0 0 -1 0 88)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGH5as8dov)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="o4qjoi0ts"/><g class="wj4kgr0on"><path class="mpcua_y1a"/><circle class="lngww5blg"/><ellipse transform="rotate(-40.01 47.63 69.711)" class="bnqjcvbze"/><ellipse transform="rotate(-36.66 38.218 59.105)" class="amfyanb_p"/><path class="i73rg1b6x"/><circle class="w7_fnbbta"/><ellipse transform="rotate(-40.01 90.714 69.671)" class="lqavankpc"/><ellipse transform="rotate(-36.66 81.224 59.117)" class="vm9sr1ylt"/></g><path class="maghh1wmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:pleading-face" /></template>
<style>
.amfyanb_p {
  cx: 38.2px;
  cy: 59.1px;
  fill: var(--svg-color--fff, #fff);
  rx: 9px;
  ry: 7.3px;
}

.bnqjcvbze {
  cx: 47.63px;
  cy: 69.72px;
  fill: var(--svg-color--fff, #fff);
  rx: 2.6px;
  ry: 2.4px;
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.i73rg1b6x {
  fill: var(--svg-color--fff, #fff);
  d: path("M85.5 48.8c9.6 0 17.4 7.8 17.4 17.4s-7.8 17.3-17.4 17.3s-17.4-7.8-17.4-17.4s7.8-17.3 17.4-17.3");
}

.lngww5blg {
  cx: 42.2px;
  cy: 63.9px;
  r: 15.4px;
  fill: var(--svg-color--422b0d, #422b0d);
}

.lqavankpc {
  cx: 90.71px;
  cy: 69.66px;
  fill: var(--svg-color--fff, #fff);
  rx: 2.6px;
  ry: 2.4px;
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.maghh1wmq {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M27.88 40.9c-2.2.4-2.3 3.6.1 3.7c4.9.1 10.2-1.7 14.3-5.5c1.5-1.3 2.8-2.9 3.7-4.5c1.2-2.2-1.6-3.7-3-2.1l-.1.1c-4 4.5-9.5 7.4-15 8.3m57.1-8.4c-1.4-1.7-4.2-.1-3 2.1c.9 1.6 2.2 3.2 3.7 4.5c4 3.7 9.4 5.6 14.3 5.5c2.5-.1 2.3-3.3.1-3.7c-5.6-.9-11.1-3.8-15.1-8.4");
}

.mpcua_y1a {
  fill: var(--svg-color--fff, #fff);
  d: path("M42.5 48.8c9.6 0 17.4 7.8 17.4 17.4s-7.8 17.3-17.4 17.3s-17.4-7.8-17.4-17.4s7.8-17.3 17.4-17.3");
}

.o4qjoi0ts {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M71.49 102.1c-.56 0-1.12-.12-1.66-.36c-5.96-2.72-11.34-.17-11.56-.06c-1.98.96-4.37.16-5.35-1.81s-.2-4.35 1.76-5.34c.36-.18 8.92-4.42 18.47-.07a4 4 0 0 1-1.66 7.64");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.vm9sr1ylt {
  cx: 81.21px;
  cy: 59.11px;
  fill: var(--svg-color--fff, #fff);
  rx: 9px;
  ry: 7.3px;
}

.w7_fnbbta {
  cx: 85.2px;
  cy: 63.9px;
  r: 15.4px;
  fill: var(--svg-color--422b0d, #422b0d);
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
