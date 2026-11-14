<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aud8xebfi"/><path class="jpd069y9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:telescopic-rod" /></template>
<style>
.aud8xebfi {
  d: path("m3.691 17.127l1.768-1.768a2.25 2.25 0 0 1 3.182 0a2.25 2.25 0 0 1 0 3.182l-1.768 1.768a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jpd069y9g {
  d: path("m8.641 13.237l2.475-2.474a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-2.474 2.475a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122m4.596-2.474l7.072-7.072m-4.773 3.006l1.767 1.767");
}

</style>
