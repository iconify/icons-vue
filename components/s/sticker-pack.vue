<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="d2uu98wig"/><path class="xoa3ht31f"/><path class="mtb_j2b3h"/><path class="n11gmnbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticker-pack" /></template>
<style>
.d2uu98wig {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75h12.5q3 0 3 3V9q0 3-2.12 5.12l-5.01 5.01Q12 21.25 9 21.25H5.75q-3 0-3-3V5.75q0-3 3-3");
}

.mtb_j2b3h {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 8.25h.01m4.99 0h.01");
}

.n11gmnbsq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12.5a4 4 0 0 0 5 1");
}

.xoa3ht31f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.22 14.03l-5.19 5.19q-.53.53-.53-.22v-3.25q0-.75.53-1.28l.44-.44q.53-.53 1.28-.53H19q.75 0 .22.53");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
