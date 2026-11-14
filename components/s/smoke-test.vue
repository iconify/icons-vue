<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk1affb5i"/><path class="ioquhu4on"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smoke-test" /></template>
<style>
.hk1affb5i {
  d: path("m8.164 8.907l.019-.252a1.13 1.13 0 0 1 1.124-1.044h.386a1.13 1.13 0 0 1 1.124 1.044l.019.252a1.5 1.5 0 0 0 .746 1.188l.692.4a1.5 1.5 0 0 0 1.401.052l.229-.111a1.13 1.13 0 0 1 1.466.452l.193.334a1.13 1.13 0 0 1-.342 1.496l-.21.143a1.5 1.5 0 0 0-.655 1.24v.798a1.5 1.5 0 0 0 .655 1.24l.21.143a1.13 1.13 0 0 1 .342 1.496l-.193.334a1.13 1.13 0 0 1-1.466.452l-.229-.111a1.5 1.5 0 0 0-1.401.052l-.692.4a1.5 1.5 0 0 0-.746 1.188l-.019.252a1.13 1.13 0 0 1-1.124 1.044h-.386a1.13 1.13 0 0 1-1.124-1.044l-.019-.252a1.5 1.5 0 0 0-.746-1.188l-.692-.4a1.5 1.5 0 0 0-1.401-.052l-.229.111a1.13 1.13 0 0 1-1.466-.452l-.193-.334a1.13 1.13 0 0 1 .342-1.496l.21-.143a1.5 1.5 0 0 0 .655-1.24v-.798a1.5 1.5 0 0 0-.655-1.24l-.21-.143a1.13 1.13 0 0 1-.342-1.496l.193-.334a1.13 1.13 0 0 1 1.466-.452l.229.111a1.5 1.5 0 0 0 1.401-.052l.692-.4a1.5 1.5 0 0 0 .746-1.188");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ioquhu4on {
  d: path("M7.25 14.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m8.25-7c-1.75-1.5 1.75-3 0-5m4.5 7c-1.75-1.5 1.75-3 0-5");
}

</style>
