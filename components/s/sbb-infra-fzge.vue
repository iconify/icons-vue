<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_i8820zz"/><circle class="cpk0fnbgt"/><path class="t2hcqacqk"/><path class="n2gz1jg9d"/><path class="seqv-2blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbb-infra-fzge" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n2gz1jg9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.893 29.993h13.45v-7.218l-1.265-1.264V20.2h10.814v4.5h4.121v7.404h-1.062v1.651H9.577v-1.149H8.34v-1.674h2.546zm4.104 0v-3.144m23.016 3.478h1.647v1.777h-1.647z");
}

.seqv-2blr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.343 23.386h7.48v3.462h-7.48zm4.688 0v3.463m-17.107 6.906a2.046 2.046 0 0 0 4.091 0m13.016 0a2.046 2.046 0 0 0 4.091 0m-18.125-5.548h-2.301");
}

.t2hcqacqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.421 15.318h39.158M12.696 29.993v-9.017h5.444v9.017");
}

.z_i8820zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.87 6.041l2.865 2.868l-2.867 2.867m-5.739 0L18.265 8.91l2.867-2.868m-2.867 2.867h11.47M24 6.041v5.736");
}

</style>
