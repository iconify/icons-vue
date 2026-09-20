<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="tw_4lub9e"/><path class="nijc13bfn"/><circle class="dljmqitxc"/><circle class="aaacpubic"/><path class="q1xwf7buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zebullo-velo-libre-service" /></template>
<style>
.aaacpubic {
  cx: 29.79px;
  cy: 25.825px;
  r: 1.94px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dljmqitxc {
  cx: 36.555px;
  cy: 25.112px;
  r: 2.945px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.nijc13bfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.456 22.21v4.779c0 .377.305.682.682.682h.205m-2.752-5.449V27c0 .377.306.683.683.683h.205m-4.94-3.65v2.252a1.365 1.365 0 0 0 2.73 0v-2.253m0 2.253v1.365m-7.832-.89a1.365 1.365 0 0 1-2.551-.676v-.887a1.365 1.365 0 1 1 2.73 0v.443h-2.73m3.828-.367a1.365 1.365 0 1 1 2.73 0v.887a1.365 1.365 0 0 1-2.73 0m0 1.365v-5.46M8.5 21.956h3.618L8.5 27.417h3.618");
}

.q1xwf7buy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.945 25.603c-.024-1.599.952-2.3 2.199-2.084m-4.81-3.576c.797.084 1.067.475 1.267.933");
}

.tw_4lub9e {
  cx: 31.867px;
  cy: 21.773px;
  r: 0.75px;
  fill: currentColor;
}

</style>
