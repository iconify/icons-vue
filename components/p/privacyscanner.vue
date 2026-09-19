<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmdcf2xqv"/><path class="r_0-wcdjh"/><path class="xs0_cp4oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:privacyscanner" /></template>
<style>
.kmdcf2xqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.159 36.056L13.874 27.52l1.75-9.957S16.107 7.18 23.94 7.387c7.661.203 8.425 9.52 8.425 9.52l1.97 10.394z");
}

.r_0-wcdjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.931 14.476C7.37 10.08 13.991 5 13.991 5s-.172 4.68 3.253 5.252m14.885 4.224C40.691 10.08 34.069 5 34.069 5s.172 4.68-3.253 5.252M17.248 29.994v-2.986l6.579-3.798l6.657 3.843v3.496M15.661 16.38h16.316M16.41 13.457h14.955m-8.634-5.71v5.506m2.583-5.506v5.506");
}

.xs0_cp4oe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.028 12.999L8.49 14.554s-1.334 11.36 5.143 20.208C14.976 36.596 23.68 43 23.68 43s8.445-5.197 10.51-7.624c6.084-7.151 5.41-20.174 5.41-20.174l-4.434-2.252");
}

</style>
