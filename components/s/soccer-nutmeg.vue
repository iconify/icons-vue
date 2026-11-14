<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-xhrp6pp"/><path class="szz_8gbpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-nutmeg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-xhrp6pp {
  d: path("m9.75 2.5l-6 18H2m12.25-18l6 18H22M8 17a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

.szz_8gbpj {
  d: path("m12.872 15.873l.009.006a1.39 1.39 0 0 1 .494 1.621l-.024.064A1.44 1.44 0 0 1 12 18.5a1.44 1.44 0 0 1-1.351-.936l-.024-.064a1.39 1.39 0 0 1 .494-1.621l.009-.006a1.5 1.5 0 0 1 1.744 0");
}

</style>
