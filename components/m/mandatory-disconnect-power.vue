<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="rbiet5byt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mandatory-disconnect-power" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.rbiet5byt {
  d: path("m15.384 7.555l1.061 1.061a1.75 1.75 0 0 1 0 2.475l-.708.707a1.75 1.75 0 0 1-2.474 0l-1.061-1.061a1.75 1.75 0 0 1 0-2.474l.707-.708a1.75 1.75 0 0 1 2.475 0m-3.536 2.829l-1.767 1.768m3.535 0l-1.768 1.767m4.066-5.833l2.829-2.829M6 13l5 5");
}

</style>
