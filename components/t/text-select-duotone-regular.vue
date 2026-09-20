<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hfa24ubxh"/><path class="n5v-07bfi"/><path class="adb205iso"/><path class="ztj49rbuu"/><path class="s8g81lbzd"/><path class="c0mmfbczh"/><path class="w-0ktubui"/><path class="n0qwiwbct"/><path class="vwjblmbrl"/><path class="rrleuowpn"/><path class="hpmnlabtt"/><path class="jm6ti-b3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:text-select-duotone-regular" /></template>
<style>
.adb205iso {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 17v3h-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c0mmfbczh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 15h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hfa24ubxh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7V4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hpmnlabtt {
  d: path("M6 9h12");
}

.jm6ti-b3r {
  d: path("M6 15h12");
}

.n0qwiwbct {
  d: path("M18 4h3v3");
}

.n5v-07bfi {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.s8g81lbzd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vwjblmbrl {
  d: path("M21 17v3h-3");
}

.w-0ktubui {
  d: path("M3 7V4h3");
}

.ztj49rbuu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 20H3v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
