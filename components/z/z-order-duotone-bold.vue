<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zwp1z3cdr"/><path class="kb4ca79fq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:z-order-duotone-bold" /></template>
<style>
.kb4ca79fq {
  d: path("M4 5h16L6 19h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zwp1z3cdr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5h16L6 19h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
