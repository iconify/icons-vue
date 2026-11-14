<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zios_kbih"/><path class="cjo8_z4cb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:muffin" /></template>
<style>
.cjo8_z4cb {
  d: path("M4.75 12.5c-1 0-1.5-.75-1.25-1.75c.75-3.5 4.25-6.25 8.5-6.25s7.75 2.75 8.5 6.25c.25 1-.25 1.75-1.25 1.75Zm5.25 0l.5 8m3.5-8l-.5 8m-5-11.25h.01M12 7.75h.01m3.49 1.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zios_kbih {
  d: path("M7.753 12.5h8.494a1.5 1.5 0 0 1 1.482 1.732l-.781 5a1.5 1.5 0 0 1-1.482 1.268H8.534a1.5 1.5 0 0 1-1.482-1.268l-.781-5A1.5 1.5 0 0 1 7.753 12.5");
}

</style>
