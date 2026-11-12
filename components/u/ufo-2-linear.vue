<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wfev_tczb"/><path class="t9y7nsmnb"/><path class="r56ehqgoa"/><path class="oyw3m0bfr"/><path class="w6loiecla"/><path class="cm0wrdgzt"/><path class="l9t7l5bzp"/><path class="gft8b4x0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ufo-2-linear" /></template>
<style>
.cm0wrdgzt {
  stroke-linejoin: round;
  d: path("M16.9999 11.0059H17");
}

.gft8b4x0a {
  stroke-linejoin: round;
  d: path("M6.98816 11.001H6.98826");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9t7l5bzp {
  stroke-linejoin: round;
  d: path("M11.9877 12H11.9878");
}

.oyw3m0bfr {
  d: path("M18 20V17");
}

.r56ehqgoa {
  d: path("M12 21V18");
}

.t9y7nsmnb {
  d: path("M12 9C15.1898 9 16.3862 8.4684 16.8003 8.18039C16.9458 8.07918 17 7.90601 17 7.72876C17 5.11714 14.8829 3 12.2712 3H11.7288C9.11714 3 7 5.11714 7 7.72876C7 7.90601 7.0542 8.07918 7.19972 8.18039C7.6138 8.4684 8.81016 9 12 9Z");
}

.w6loiecla {
  d: path("M6 20V17");
}

.wfev_tczb {
  d: path("M16.9716 7.20715L17 7.21093C19.989 7.93257 22 9.28138 22 10.8262C22 13.1313 17.5228 14.9999 12 14.9999C6.47715 14.9999 2 13.1313 2 10.8262C2 9.28138 4.01099 7.93257 7 7.21093L7.02863 7.20557");
}

</style>
