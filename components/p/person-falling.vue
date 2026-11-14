<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2qsjr_jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-falling" /></template>
<style>
.u2qsjr_jd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 5.938a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m1.25 2.165l-3.5 6.062M7.804 7.268l10.392 6m-7.446.897l-5.781 3.013m5.781-3.013l.281 6.513M3.5 11q0-5.5 5-8");
}

</style>
