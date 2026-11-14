<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rrw_6nbku"/><path class="m_-7swdns"/><path class="jle0ue-hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-and-compass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jle0ue-hh {
  d: path("m17.625 15.625l.343.754a1.5 1.5 0 0 1 0 1.242l-.343.754a.687.687 0 0 1-1.25 0l-.343-.754a1.5 1.5 0 0 1 0-1.242l.343-.754a.687.687 0 0 1 1.25 0");
}

.m_-7swdns {
  d: path("M12 17a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

.rrw_6nbku {
  d: path("M9.239 16.913L8 16.5l-5.5 2v-13l5.5-2l6 2l5.5-2v6.071M8 3.5v13m6-11v4.3");
}

</style>
