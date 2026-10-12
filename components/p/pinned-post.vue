<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rvlakxbze"/><path class="j0vcpfvpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinned-post" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0vcpfvpk {
  d: path("M6.25 13h5m-5 4h5.5m2.87-11.38l3.76 3.76q.42.42.49-.18l.21-1.63q.07-.6.5-1.02l1.09-1.1q.43-.42.01-.84l-1.29-1.29q-.42-.42-.84.01l-1.1 1.09q-.42.43-1.02.5l-1.63.21q-.6.07-.18.49M16.5 7.5l-3 3");
}

.rvlakxbze {
  width: 12.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 3px;
}

</style>
