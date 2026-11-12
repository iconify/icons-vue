<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t9y7nsmnb"/><path class="r56ehqgoa"/><path class="rg4xnib3l"/><path class="kejfovb9p"/><path class="k-84xlb3p"/><path class="q55h_0lpu"/><path class="glgfkxb0q"/><path class="uovqdhbyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-2-line-duotone" /></template>
<style>
.glgfkxb0q {
  stroke-linejoin: round;
  d: path("M6.98816 11H6.98826");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-84xlb3p {
  stroke-linejoin: round;
  d: path("M16.9999 11.0049H17");
}

.kejfovb9p {
  d: path("M6 20V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.q55h_0lpu {
  stroke-linejoin: round;
  d: path("M11.9877 11.999H11.9878");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r56ehqgoa {
  d: path("M12 21V18");
}

.rg4xnib3l {
  d: path("M18 20V17");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t9y7nsmnb {
  d: path("M12 9C15.1898 9 16.3862 8.4684 16.8003 8.18039C16.9458 8.07918 17 7.90601 17 7.72876C17 5.11714 14.8829 3 12.2712 3H11.7288C9.11714 3 7 5.11714 7 7.72876C7 7.90601 7.0542 8.07918 7.19972 8.18039C7.6138 8.4684 8.81016 9 12 9Z");
}

.uovqdhbyi {
  d: path("M16.9716 7.20763L17 7.21142C19.989 7.93306 22 9.28187 22 10.8267C22 13.1317 17.5228 15.0003 12 15.0003C6.47715 15.0003 2 13.1317 2 10.8267C2 9.28187 4.01099 7.93306 7 7.21142L7.02863 7.20605");
}

</style>
