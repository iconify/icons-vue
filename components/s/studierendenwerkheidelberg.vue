<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wksgihbjz"/><path class="y5ezz_boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:studierendenwerkheidelberg" /></template>
<style>
.wksgihbjz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41 32.5l2.5-24H14c-3.3 0-6.658 3.718-7 7l-2.5 24H34c3.3 0 6.658-3.718 7-7");
}

.y5ezz_boj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.1 20.6a2.38 2.38 0 0 0 2 .9h1.2a2 2 0 0 0 0-4H14a2 2 0 0 1 0-4h1.2a2.15 2.15 0 0 1 2 .9m5.504-.9v8m5.296-8l2 8l2-8l2 8l2-8m-19 17h5.3m3.4 4v-8H27a4 4 0 0 1 0 8Zm-5.7-21h5.408m-3.108 13v8m-5.3-8v8");
}

</style>
