<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pjk88gb4s"/><path class="gs9e0-szi"/><path class="poc74rbsn"/><path class="s1rf7f7io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:standing-fan" /></template>
<style>
.gs9e0-szi {
  d: path("M12 8.5za1.25 1.25 0 0 1 1.25 1.25v1.75A1.25 1.25 0 0 1 12 12.75a1.25 1.25 0 0 1-1.25-1.25V9.75A1.25 1.25 0 0 1 12 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pjk88gb4s {
  d: path("M5.25 8.75a6.75 6.75 0 1 0 13.5 0a6.75 6.75 0 1 0-13.5 0M12 15.5v6m-4.5 0h9");
}

.poc74rbsn {
  d: path("M12.217 8.875za1.25 1.25 0 0 1-1.708.458l-1.516-.875a1.25 1.25 0 0 1-.457-1.708a1.25 1.25 0 0 1 1.707-.458l1.516.875a1.25 1.25 0 0 1 .458 1.708");
}

.s1rf7f7io {
  d: path("M11.783 8.875za1.25 1.25 0 0 1 .458-1.708l1.516-.875a1.25 1.25 0 0 1 1.707.458a1.25 1.25 0 0 1-.457 1.708l-1.516.875a1.25 1.25 0 0 1-1.708-.458");
}

</style>
