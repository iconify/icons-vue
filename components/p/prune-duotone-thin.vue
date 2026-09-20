<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydrfk9w6p"/><path class="jpfwhpbab"/><path class="ww1qa5bbn"/><path class="i_15enoqb"/><path class="rb2jzlb5g"/><path class="mpjdm200q"/><path class="ngnirel9c"/><path class="hcq4p1b2v"/><path class="b1a3u6bfq"/><path class="ax4bccbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prune-duotone-thin" /></template>
<style>
.ax4bccbjb {
  d: path("m20 7 -4 4");
}

.b1a3u6bfq {
  d: path("m16 7 4 4");
}

.hcq4p1b2v {
  d: path("M6 15h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_15enoqb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 7 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jpfwhpbab {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.ngnirel9c {
  d: path("M6 9h8");
}

.rb2jzlb5g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m20 7 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ww1qa5bbn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ydrfk9w6p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
