<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxnzn9nmw"/><path class="liycxk3hh"/><circle class="kd06ylh6g"/><path class="o8b07n22g"/><path class="o--tz19gs"/><path class="dt-vgkbui"/><path class="nln6tjbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-square-2-line-duotone" /></template>
<style>
.dt-vgkbui {
  d: path("M5 16L6 16");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kd06ylh6g {
  cx: 14px;
  cy: 8px;
  r: 2px;
}

.liycxk3hh {
  d: path("M10 14C11.1046 14 12 14.8954 12 16C12 17.1046 11.1046 18 10 18C8.89543 18 8 17.1046 8 16C8 14.8954 8.89543 14 10 14Z");
}

.lxnzn9nmw {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.nln6tjbcr {
  d: path("M19 8L18 8");
}

.o--tz19gs {
  d: path("M10 8L5 8");
}

.o8b07n22g {
  d: path("M14 16L19 16");
}

</style>
