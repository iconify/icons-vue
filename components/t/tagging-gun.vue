<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_zwtwbfa"/><path class="qnbzo-bcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tagging-gun" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnbzo-bcs {
  d: path("M11.091 10.5h.984a1.75 1.75 0 0 1 1.743 1.916l-.667 7A1.75 1.75 0 0 1 11.409 21h-.984a1.75 1.75 0 0 1-1.743-1.916l.667-7a1.75 1.75 0 0 1 1.742-1.584M18 7.5h3.5m-15 3V13c0 1.5.75 2.5 2 2.5M7 4.5v-2m3.5 2v-2");
}

.s_zwtwbfa {
  d: path("M6.5 4.5H15a3 3 0 0 1 3 3a3 3 0 0 1-3 3H6.5a3 3 0 0 1-3-3a3 3 0 0 1 3-3");
}

</style>
