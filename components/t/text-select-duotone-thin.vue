<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_h_wizsz"/><path class="lxo7srmgm"/><path class="sql450bon"/><path class="uv_2x-bxw"/><path class="itae-9boz"/><path class="rs-eeii7j"/><path class="w-0ktubui"/><path class="n0qwiwbct"/><path class="vwjblmbrl"/><path class="rrleuowpn"/><path class="hpmnlabtt"/><path class="jm6ti-b3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-select-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hpmnlabtt {
  d: path("M6 9h12");
}

.i_h_wizsz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7V4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.itae-9boz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jm6ti-b3r {
  d: path("M6 15h12");
}

.lxo7srmgm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n0qwiwbct {
  d: path("M18 4h3v3");
}

.rrleuowpn {
  d: path("M6 20H3v-3");
}

.rs-eeii7j {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sql450bon {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 17v3h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uv_2x-bxw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 20H3v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vwjblmbrl {
  d: path("M21 17v3h-3");
}

.w-0ktubui {
  d: path("M3 7V4h3");
}

</style>
