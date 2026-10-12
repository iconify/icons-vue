<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz7c6rbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:souk-tent-sharp" /></template>
<style>
.uz7c6rbwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 6.75l7.7-3.65l.8-.35l.8.35l7.7 3.65V8.5a1.7 1.7 0 0 1-3.4 0a1.7 1.7 0 0 1-3.4 0a1.7 1.7 0 0 1-3.4 0a1.7 1.7 0 0 1-3.4 0a1.7 1.7 0 0 1-3.4 0Zm1 4v10.5m15-10.5v10.5m-15-4.5h15m-11.5 0c0-2.5 1.75-4 4-4s4 1.5 4 4Z");
}

</style>
