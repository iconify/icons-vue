<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g00uv-b-x"/><path class="koh8ckbdb"/><path class="k2mg4f2ls"/><path class="ho-p1ibpr"/><path class="cf0d2ub2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:out-for-delivery-outline-thin" /></template>
<style>
.cf0d2ub2o {
  d: path("M8.5 8.5 11 11l-2.5 2.5");
}

.g00uv-b-x {
  d: path("M4 5h9a2 2 0 0 1 2 2v3h3.5l2.5 2.5V15a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ho-p1ibpr {
  d: path("M5 11h6");
}

.k2mg4f2ls {
  d: path("M15 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.koh8ckbdb {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
