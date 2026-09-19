<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBmhpVd)" class="sxgonibhp"/><path fill="url(#icvY4bC)" class="sxgonibhp"/><path fill="url(#i24CBKc)" class="sxgonibhp"/><defs><radialGradient id="icvY4bC" cx="0" cy="0" r="1" gradientTransform="rotate(92.942 .75 15.923)scale(13.7536 21.0011)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="tcoi14v6o"/><stop offset=".704" class="haogwie1v"/></radialGradient><radialGradient id="i24CBKc" cx="0" cy="0" r="1" gradientTransform="rotate(130.357 10.527 13.82)scale(1.629)" gradientUnits="userSpaceOnUse"><stop class="wk-y_-1qb"/><stop offset="1" class="cypk33s0r"/></radialGradient><linearGradient id="iBmhpVd" x1="15.985" x2="15.985" y1="12.93" y2="19.05" gradientUnits="userSpaceOnUse"><stop class="uw6ct3bwa"/><stop offset=".214" class="uzo543nom"/><stop offset=".335" class="lkeurab-x"/><stop offset=".523" class="i8hjxcl1d"/><stop offset=".863" class="gt6rl0ltw"/><stop offset="1" class="d_6xy98jp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:minus" /></template>
<style>
.cypk33s0r {
  stop-color: var(--svg-color--9d93d3, #9D93D3);
  stop-opacity: 0;
}

.d_6xy98jp {
  stop-color: var(--svg-color--6035be, #6035BE);
}

.ft5dv1b6b {
  fill: none;
}

.gt6rl0ltw {
  stop-color: var(--svg-color--8842ec, #8842EC);
}

.haogwie1v {
  stop-color: var(--svg-color--41366a, #41366A);
}

.i8hjxcl1d {
  stop-color: var(--svg-color--7966c1, #7966C1);
}

.lkeurab-x {
  stop-color: var(--svg-color--897ec1, #897EC1);
}

.sxgonibhp {
  d: path("M2 15.99c0-1.69 1.38-3.06 3.06-3.06h21.85c1.69 0 3.06 1.38 3.06 3.06c0 1.69-1.38 3.06-3.06 3.06H5.06C3.38 19.05 2 17.67 2 15.99");
}

.tcoi14v6o {
  stop-color: var(--svg-color--423473, #423473);
  stop-opacity: 0;
}

.uw6ct3bwa {
  stop-color: var(--svg-color--655898, #655898);
}

.uzo543nom {
  stop-color: var(--svg-color--8276bd, #8276BD);
}

.wk-y_-1qb {
  stop-color: var(--svg-color--9c92d2, #9C92D2);
}

</style>
