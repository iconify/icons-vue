<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGuw9kS7yO"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="r1uw6x1jt"/><path class="mkcb18b2m"/><path class="czj_m1b1k"/><path clip-rule="evenodd" class="z8g30dfux"/><path class="njf90pb2k"/><path class="bidltu3do"/></mask></defs><circle mask="url(#SVGuw9kS7yO)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:printer-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bidltu3do {
  fill: var(--svg-color--000, #000);
  d: path("M10 19a.5.5 0 0 1 0-1h6a.5.5 0 0 1 0 1zm0-2a.5.5 0 0 1 0-1h6a.5.5 0 0 1 0 1z");
}

.czj_m1b1k {
  fill: var(--svg-color--000, #000);
  d: path("M7 9h12a3 3 0 0 1 3 3v5a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3");
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.mkcb18b2m {
  fill: var(--svg-color--000, #000);
  d: path("M9 6v4a1 1 0 0 1-2 0V6c0-1.068.776-2 1.833-2h8.334C18.224 4 19 4.932 19 6v4a1 1 0 1 1-2 0V6z");
}

.njf90pb2k {
  fill: var(--svg-color--000, #000);
  d: path("M9 19.8V15a1 1 0 1 0-2 0v4.8c0 1.154.727 2.2 1.833 2.2h8.334C18.273 22 19 20.954 19 19.8V15a1 1 0 1 0-2 0v4.8a.7.7 0 0 1-.029.2H9.029A.7.7 0 0 1 9 19.8");
}

.r1uw6x1jt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8 10V6c0-.552.373-1 .833-1h8.334c.46 0 .833.448.833 1v4");
}

.z8g30dfux {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8 15v4.8c0 .663.373 1.2.833 1.2h8.334c.46 0 .833-.537.833-1.2V15");
}

</style>
