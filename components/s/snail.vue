<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uezvljqyi"/><circle class="zs9gv_blq"/><path class="rxrhb0bxg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:snail" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxrhb0bxg {
  d: path("M12 12.25A2.25 2.25 0 1 1 9.75 10m8.75.56l-1-4.06m3 4.06l.75-3.81");
}

.uezvljqyi {
  d: path("M2.75 20.5h16.5c1.1 0 2-.9 2-2V12a1.75 1.75 0 0 0-3.5 0v5.5H4.25c-.85 0-1.5.65-1.5 1.5Z");
}

.zs9gv_blq {
  cx: 9.75px;
  cy: 12.25px;
  r: 5.25px;
}

</style>
