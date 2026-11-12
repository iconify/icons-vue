<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k66tt2kvs"/><path class="hq-5njbjh"/><path class="khpsiybcv"/><path class="fbw3i1bgm"/><path class="t0r576ckt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suitcase-tag-linear" /></template>
<style>
.fbw3i1bgm {
  d: path("M6 6.5V15M6 18.5V21.5");
}

.hq-5njbjh {
  d: path("M16 6C16 4.11438 16 3.17157 15.4142 2.58579C14.8284 2 13.8856 2 12 2C10.1144 2 9.17157 2 8.58579 2.58579C8 3.17157 8 4.11438 8 6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k66tt2kvs {
  d: path("M10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C22 19.6569 22 17.7712 22 14C22 10.2288 22 8.34315 20.8284 7.17157C19.6569 6 17.7712 6 14 6H10C6.22876 6 4.34315 6 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22Z");
}

.khpsiybcv {
  stroke-linejoin: round;
  d: path("M6 15H10C10.4714 15 10.7071 15 10.8536 15.1464C11 15.2929 11 15.5286 11 16V17C11 17.4714 11 17.7071 10.8536 17.8536C10.7071 18 10.4714 18 10 18H6C5.5286 18 5.29289 18 5.14645 17.8536C5 17.7071 5 17.4714 5 17V16C5 15.5286 5 15.2929 5.14645 15.1464C5.29289 15 5.5286 15 6 15Z");
}

.t0r576ckt {
  d: path("M18 6.5V21.5");
}

</style>
