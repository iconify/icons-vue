<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="g31q_jb0h"/><path class="mxzk029nb"/><path class="zrsj1cc7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:retry-policy-outline-thin" /></template>
<style>
.d8z1r1beo {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.g31q_jb0h {
  d: path("M9 10v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxzk029nb {
  d: path("M12 10v4");
}

.wzx0dxb2r {
  d: path("m12 2 3 3 -3 3");
}

.zrsj1cc7l {
  d: path("M15 10v4");
}

</style>
