<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hrwqdnb5i"/><rect class="zhjydmbjk"/><circle class="ukvmc8bfw"/><path class="ziql97jnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:portfolio" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrwqdnb5i {
  d: path("M9 7V5.5A1.5 1.5 0 0 1 10.5 4h3A1.5 1.5 0 0 1 15 5.5V7");
}

.ukvmc8bfw {
  cx: 12px;
  cy: 14px;
  r: 4px;
}

.zhjydmbjk {
  width: 18px;
  height: 14px;
  x: 3px;
  y: 7px;
  rx: 2.5px;
}

.ziql97jnu {
  d: path("M12 10v4h4");
}

</style>
