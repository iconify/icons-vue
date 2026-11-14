<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vi-y5jnwu"/><path class="kc-9v7ady"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:settings-wrench" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kc-9v7ady {
  d: path("M15.5 3.75V7A1.5 1.5 0 0 0 17 8.5h3.25M4.5 19.5L12 12m5.704 4.103l.001-.04a.53.53 0 0 1 .53-.516h.03a.53.53 0 0 1 .53.516l.001.04a.85.85 0 0 0 .425.715a.85.85 0 0 0 .832.011l.035-.019a.53.53 0 0 1 .711.201l.016.026a.53.53 0 0 1-.183.716l-.033.021a.85.85 0 0 0-.407.726a.85.85 0 0 0 .407.726l.033.021a.53.53 0 0 1 .183.716l-.016.026a.53.53 0 0 1-.711.201l-.035-.019a.85.85 0 0 0-.832.011a.85.85 0 0 0-.425.715l-.001.04a.53.53 0 0 1-.53.516h-.03a.53.53 0 0 1-.53-.516l-.001-.04a.85.85 0 0 0-.425-.715a.85.85 0 0 0-.832-.011l-.035.019a.53.53 0 0 1-.711-.201l-.016-.026a.53.53 0 0 1 .183-.716l.033-.021a.85.85 0 0 0 .407-.726a.85.85 0 0 0-.407-.726l-.033-.021a.53.53 0 0 1-.183-.716l.016-.026a.53.53 0 0 1 .711-.201l.035.019a.85.85 0 0 0 .832-.011a.85.85 0 0 0 .425-.715");
}

.vi-y5jnwu {
  d: path("M20.25 8.5a4.75 4.75 0 1 1-4.75-4.75");
}

</style>
