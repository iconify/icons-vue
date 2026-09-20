<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gih_8vbyg"/><path class="jf_v1slmw"/><path class="pg-wrtbze"/><path class="p14ag28op"/><path class="e8rvqbc4z"/><path class="yy262cc0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunny-duotone-thin" /></template>
<style>
.e8rvqbc4z {
  d: path("m4 20 3 -3");
}

.gih_8vbyg {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf_v1slmw {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

.p14ag28op {
  d: path("m20 4 -3 3");
}

.pg-wrtbze {
  d: path("m4 4 3 3");
}

.yy262cc0h {
  d: path("m20 20 -3 -3");
}

</style>
