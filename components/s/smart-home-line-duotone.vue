<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cyl9zjekg"/><path class="wo5j09bdc"/><path class="yt8px34lk"/><path class="vciis7brh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smart-home-line-duotone" /></template>
<style>
.cyl9zjekg {
  d: path("M13.9999 22C17.7711 22 19.6567 22 20.8283 20.7881C21.9999 19.5763 21.9999 17.6258 21.9999 13.725V12.2039C21.9999 9.91549 21.9999 8.77128 21.4807 7.82274C20.9615 6.87421 20.0129 6.28551 18.1158 5.10812L16.1158 3.86687C14.1105 2.62229 13.1078 2 11.9999 2C10.8919 2 9.88925 2.62229 7.8839 3.86687L5.8839 5.10813C3.98681 6.28551 3.03827 6.87421 2.51907 7.82274C2.20149 8.40293 2.07817 9.05632 2.03027 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vciis7brh {
  d: path("M2 19C3.65685 19 5 20.3431 5 22");
}

.wo5j09bdc {
  d: path("M2 13C6.97056 13 11 17.0294 11 22");
}

.yt8px34lk {
  d: path("M2 16C5.31371 16 8 18.6863 8 22");
}

</style>
