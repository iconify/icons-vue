<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="mk0cvynsk"/><path class="a0f0f2w0j"/><path class="sj5kv5bwz"/><path class="abnm6smsv"/><path class="mfc7nxp-y"/><path class="f9z-0cczq"/><path class="ynh89jb5g"/><path class="me177l4bh"/><path class="nxt-uwbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pagination-offset-duotone-bold" /></template>
<style>
.a0f0f2w0j {
  fill: currentColor;
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.f9z-0cczq {
  d: path("M9 10.5h6");
}

.me177l4bh {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.mk0cvynsk {
  fill: currentColor;
  d: path("M7 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nxt-uwbql {
  d: path("M15 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sj5kv5bwz {
  fill: currentColor;
  d: path("M15 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ynh89jb5g {
  d: path("M7 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
