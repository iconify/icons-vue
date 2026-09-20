<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":425};
const content = `<defs><radialGradient id="SVGHREXXgVz" cx="16.423%" cy="143%" r="295.571%" fx="16.423%" fy="143%"><stop offset="0%" class="admre4k9r"/><stop offset="100%" class="pch-4c4id"/></radialGradient><radialGradient id="SVG6UmI6bDY" cx="16.423%" cy="-43%" r="357.004%" fx="16.423%" fy="-43%"><stop offset="0%" class="admre4k9r"/><stop offset="100%" class="pch-4c4id"/></radialGradient><radialGradient id="SVGBZa6xpUb" cx="11.467%" cy="-40.458%" r="343.189%" fx="11.467%" fy="-40.458%"><stop offset="0%" class="tzrql9bop"/><stop offset="100%" class="w-ofocfpq"/></radialGradient><linearGradient id="SVGvlJZFd9v" x1="50%" x2="50%" y1="-352.926%" y2="96.718%"><stop offset="0%" class="x080uzdhk"/><stop offset="100%" class="pnc1a7brq"/></linearGradient><linearGradient id="SVGZVLNw9hg" x1="50%" x2="50%" y1="-2.808%" y2="428.759%"><stop offset="0%" class="x080uzdhk"/><stop offset="100%" class="pnc1a7brq"/></linearGradient></defs><path fill="url(#SVGvlJZFd9v)" class="ckk0m_bto"/><path fill="url(#SVGZVLNw9hg)" class="c78602byw"/><path fill="url(#SVGHREXXgVz)" class="qt55ldbzn"/><path fill="url(#SVG6UmI6bDY)" class="j60m0ncit"/><path fill="url(#SVGBZa6xpUb)" class="bcsvwwzzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:snap-svg" /></template>
<style>
.admre4k9r {
  stop-color: var(--svg-color--00bc85, #00bc85);
}

.bcsvwwzzt {
  d: path("m255.004 298.216l-197.415-98.25V98.182L0 62.23v173.702l255.004 126.321z");
}

.c78602byw {
  d: path("M57.602 98.175v-.02l69.93-34.107l69.934 34.106L255.004 62.2L127.484 0L0 62.18v.055l57.554 35.964z");
}

.ckk0m_bto {
  d: path("M65.7 330.3L.107 362.385l127.292 62l127.64-62.194l-65.76-32.539l-61.928 30.754z");
}

.j60m0ncit {
  d: path("M196.678 99.41v100.768l-70.342 34.424l64.686 32.339l62.979-30.797V62.19l-57.323 35.976z");
}

.pch-4c4id {
  stop-color: var(--svg-color--149d91, #149d91);
}

.pnc1a7brq {
  stop-color: var(--svg-color--002639, #002639);
}

.qt55ldbzn {
  d: path("m.156 298.428l62.915-30.803l64.714 32.042L.156 362.462z");
}

.tzrql9bop {
  stop-color: var(--svg-color--004473, #004473);
}

.w-ofocfpq {
  stop-color: var(--svg-color--00345f, #00345f);
}

.x080uzdhk {
  stop-color: var(--svg-color--002e3b, #002e3b);
}

</style>
