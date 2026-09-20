<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-0ktubui"/><path class="n0qwiwbct"/><path class="vwjblmbrl"/><path class="rrleuowpn"/><path class="hpmnlabtt"/><path class="jm6ti-b3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-select-outline-regular" /></template>
<style>
.hpmnlabtt {
  d: path("M6 9h12");
}

.jm6ti-b3r {
  d: path("M6 15h12");
}

.n0qwiwbct {
  d: path("M18 4h3v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrleuowpn {
  d: path("M6 20H3v-3");
}

.vwjblmbrl {
  d: path("M21 17v3h-3");
}

.w-0ktubui {
  d: path("M3 7V4h3");
}

</style>
