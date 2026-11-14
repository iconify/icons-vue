<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rr5o8luwc"/><path class="ui72q6bza"/><path class="rpf5c_bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ski-school" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpf5c_bpp {
  d: path("M16 17.25v2.5q2 1.5 4 0v-2.5");
}

.rr5o8luwc {
  d: path("m3.5 19l13-13q1.25-1.25 2.75-1");
}

.ui72q6bza {
  d: path("M14.242 14.242L6 6Q4.75 4.75 3.25 5M16.5 16l.829-.415a1.5 1.5 0 0 1 1.342 0L19.5 16a.839.839 0 0 1 0 1.5l-.829.415a1.5 1.5 0 0 1-1.342 0L16.5 17.5a.839.839 0 0 1 0-1.5");
}

</style>
