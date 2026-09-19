<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dlf8lebna"/><g class="y9tr6bcfx"><circle class="z73jwbbls"/><path class="tqw97ibps"/></g><g class="y9tr6bcfx"><circle class="nvn715voe"/><path class="uzx-xxkcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tradfrimelodi" /></template>
<style>
.dlf8lebna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.935 43.5h14.13M24 14.808V43.5m5.047-39H18.953l-5 10.308h20.094z");
}

.nvn715voe {
  cx: 18.658px;
  cy: 26.951px;
  r: 1.723px;
}

.tqw97ibps {
  d: path("m33 26.907l-3.224.686l2.017 8.631");
}

.uzx-xxkcd {
  d: path("m21.067 21.054l-1.924.41l1.203 5.149");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z73jwbbls {
  cx: 28.963px;
  cy: 36.79px;
  r: 2.888px;
}

</style>
