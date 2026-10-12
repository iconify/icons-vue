<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ixscbdo9e"/><circle class="xhuo7yavf"/><path class="zhbvr361s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waypoint" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ixscbdo9e {
  d: path("M12 16.25c-.3 0-.55-.12-.75-.33C9 13.6 6.5 11.4 6.5 8.75a5.5 5.5 0 0 1 11 0c0 2.65-2.5 4.85-4.75 7.17c-.2.21-.45.33-.75.33");
}

.xhuo7yavf {
  cx: 12px;
  cy: 8.75px;
  r: 1.75px;
}

.zhbvr361s {
  d: path("M3.25 20.25h3.5m3.5 0h3.5m3.5 0h3.5");
}

</style>
