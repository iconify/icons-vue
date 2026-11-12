<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sdign3bjj"/><path class="n30k0z4xd"/><path class="iyj9s7b1n"/><path class="u740ad0lr"/><path class="uyg1ssbvd"/><path class="sk8067bdl"/><path class="lkrvd9bst"/><path class="z9bh2umqw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyj9s7b1n {
  d: path("M5.50036 15.5L4.5 17.5");
}

.lkrvd9bst {
  stroke-linejoin: round;
  d: path("M6.98828 12.001H6.98838");
}

.n30k0z4xd {
  d: path("M12 16V19");
}

.sdign3bjj {
  d: path("M12 10C15.1898 10 16.3862 9.4684 16.8003 9.18039C16.9458 9.07918 17 8.90601 17 8.72876C17 6.11714 14.8829 4 12.2712 4H11.7288C9.11714 4 7 6.11714 7 8.72876C7 8.90601 7.0542 9.07918 7.19972 9.18039C7.6138 9.4684 8.81016 10 12 10Z");
}

.sk8067bdl {
  stroke-linejoin: round;
  d: path("M11.9878 13H11.9879");
}

.u740ad0lr {
  d: path("M18.4996 15.5L19.5 17.5");
}

.uyg1ssbvd {
  stroke-linejoin: round;
  d: path("M17 12.0059H17.0001");
}

.z9bh2umqw {
  d: path("M16.9716 8.20763L17 8.21142C19.989 8.93306 22 10.2819 22 11.8267C22 14.1317 17.5228 16.0003 12 16.0003C6.47715 16.0003 2 14.1317 2 11.8267C2 10.2819 4.01099 8.93306 7 8.21142L7.02863 8.20605");
}

</style>
