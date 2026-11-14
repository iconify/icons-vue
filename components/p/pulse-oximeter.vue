<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-bzw753z"/><path class="hd14wmskx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pulse-oximeter" /></template>
<style>
.hd14wmskx {
  d: path("M5.75 8h4A3.25 3.25 0 0 1 13 11.25a3.25 3.25 0 0 1-3.25 3.25h-4a3.25 3.25 0 0 1-3.25-3.25A3.25 3.25 0 0 1 5.75 8M5 11.25h5.5M14.25 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5.5 1c0-.75 1.75-.75 1.75.25c0 .75-1.75 1.5-1.75 2.25h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-bzw753z {
  d: path("M4 21.5V13q0-.184.018-.368q.018-.183.054-.364q.036-.18.089-.357q.054-.176.124-.346t.158-.333t.189-.315q.102-.154.219-.296t.247-.273q.131-.13.273-.247t.296-.219t.315-.189q.163-.087.333-.158q.17-.07.346-.124q.177-.053.357-.089q.181-.036.364-.054q.184-.018.368-.018t.368.018t.364.054t.357.089t.346.124t.333.158t.315.189q.154.102.296.219t.273.247t.247.273t.219.296t.189.315q.087.163.158.333q.07.17.124.346q.053.177.089.357q.036.181.054.364q.018.184.018.368v4.919m0 .2V21.5");
}

</style>
