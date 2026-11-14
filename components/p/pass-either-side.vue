<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kb5a7sb9z"/><path class="pb527hbxe"/><path class="fjynpzbbg"/><path class="h5vg4zb1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pass-either-side" /></template>
<style>
.fjynpzbbg {
  d: path("m3 18.25l2.25 2.25l2.25-2.25M14 3.5c0 3 4.75 2.75 4.75 6.75V20.5");
}

.h5vg4zb1t {
  d: path("m16.5 18.25l2.25 2.25L21 18.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kb5a7sb9z {
  fill: currentColor;
  d: path("M12 10za1.75 1.75 0 0 1 1.75 1.75v5A1.75 1.75 0 0 1 12 18.5a1.75 1.75 0 0 1-1.75-1.75v-5A1.75 1.75 0 0 1 12 10");
}

.pb527hbxe {
  d: path("M10 3.5c0 3-4.75 2.75-4.75 6.75V20.5");
}

</style>
