<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="swsab_86e"/><circle class="fw5rt46mg"/><path class="clsyeylvw"/><path class="jqt39-bbm"/><path class="q6cbe7bnx"/><path class="kwa31tbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:usb-linear" /></template>
<style>
.clsyeylvw {
  stroke-linejoin: round;
  d: path("M12 18V15V2M10 5L12 2L14 5");
}

.fw5rt46mg {
  cx: 6px;
  cy: 6px;
  r: 1px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqt39-bbm {
  d: path("M6 7V9.55848C6 10.4193 6.55086 11.1836 7.36754 11.4558L10.6325 12.5442C11.4491 12.8164 12 13.5807 12 14.4415V15");
}

.kwa31tbhm {
  d: path("M17 9C17 8.5286 17 8.29289 17.1464 8.14645C17.2929 8 17.5286 8 18 8C18.4714 8 18.7071 8 18.8536 8.14645C19 8.29289 19 8.5286 19 9C19 9.4714 19 9.70711 18.8536 9.85355C18.7071 10 18.4714 10 18 10C17.5286 10 17.2929 10 17.1464 9.85355C17 9.70711 17 9.4714 17 9Z");
}

.q6cbe7bnx {
  d: path("M18 10V12.5585C18 13.4193 17.4491 14.1836 16.6325 14.4558L13.3675 15.5442C12.5509 15.8164 12 16.5807 12 17.4415V18");
}

.swsab_86e {
  cx: 12px;
  cy: 20px;
  r: 2px;
}

</style>
