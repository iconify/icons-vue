<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="dy9tza2iq"/><path class="v1ql_tt0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:review-reply-outline-thin" /></template>
<style>
.dy9tza2iq {
  d: path("M8 10.5h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.v1ql_tt0s {
  d: path("M10.5 8 8 10.5l2.5 2.5");
}

.yomctlb4k {
  d: path("M7 17v4l4 -4");
}

</style>
