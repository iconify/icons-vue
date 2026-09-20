<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vws5wpblq"/><path class="osltrsbvo"/><path class="eimg1ibhu"/><path class="m89us6n4x"/><path class="ri2m-q_tv"/><path class="f26bn-hui"/><path class="l517yxbln"/><path class="dti01qb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:merge-queue-duotone-thin" /></template>
<style>
.dti01qb8s {
  d: path("M16 9v6");
}

.eimg1ibhu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f26bn-hui {
  d: path("M8 9v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l517yxbln {
  d: path("M12 9v6");
}

.m89us6n4x {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.osltrsbvo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.vws5wpblq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
