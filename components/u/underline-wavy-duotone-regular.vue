<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="dx4yo_bup"/><path class="hdfne9bfa"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="i80sg_6wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:underline-wavy-duotone-regular" /></template>
<style>
.dx4yo_bup {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hdfne9bfa {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 16 2.5 -2.5L8 16l2.5 -2.5L13 16l2.5 -2.5L18 16l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i80sg_6wn {
  d: path("m3 16 2.5 -2.5L8 16l2.5 -2.5L13 16l2.5 -2.5L18 16l2.5 -2.5");
}

.j835zw5-z {
  d: path("M3 9h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s1ajs51ib {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
