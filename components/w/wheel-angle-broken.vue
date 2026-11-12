<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hg3yhdcod"/><path class="kflwj50xz"/><path class="cihr55ejt"/><path class="sdb9eeb1p"/><path class="z3hbucb_l"/><path class="id9cc5l6h"/><path class="pf95emypg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-angle-broken" /></template>
<style>
.cihr55ejt {
  d: path("M7.5 22C9.98528 22 12 17.5228 12 12C12 6.47715 9.98528 2 7.5 2");
}

.hg3yhdcod {
  d: path("M21 12C21 17.5228 18.9853 22 16.5 22M16.5 2C18.3453 2 19.9312 4.46819 20.6256 8");
}

.id9cc5l6h {
  d: path("M7.5 22L16.5 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kflwj50xz {
  d: path("M3 12C3 6.47715 5.01472 2 7.5 2C9.98528 2 12 6.47715 12 12C12 17.5228 9.98528 22 7.5 22C5.65471 22 4.06884 19.5318 3.37444 16");
}

.pf95emypg {
  d: path("M9 12H8");
}

.sdb9eeb1p {
  d: path("M9 12C9 15.3137 8.32843 18 7.5 18C6.67157 18 6 15.3137 6 12C6 8.68629 6.67157 6 7.5 6C8.32843 6 9 8.68629 9 12Z");
}

.z3hbucb_l {
  d: path("M7.5 2L16.5 2");
}

</style>
