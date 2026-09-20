<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v8848ubds"/><path class="u3-6xcbbc"/><path class="ckawxab4i"/><path class="egu9ezovw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:priority-duotone-thin" /></template>
<style>
.ckawxab4i {
  d: path("m4 11 8 -8 8 8");
}

.egu9ezovw {
  d: path("m4 20 8 -8 8 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u3-6xcbbc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 20 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v8848ubds {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
