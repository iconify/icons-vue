<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="kmqwfkbdg"/><circle class="apefvdupm"/><path class="p_qjaxbml"/><path class="r_3lljbpa"/><path class="oazq83bmy"/><path class="lpogj4adh"/><circle class="doy9q4b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:usb-circle-line-duotone" /></template>
<style>
.apefvdupm {
  cx: 8px;
  cy: 9px;
  r: 1px;
}

.doy9q4b5f {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmqwfkbdg {
  cx: 12px;
  cy: 17px;
  r: 1px;
}

.lpogj4adh {
  d: path("M15 10C15 9.5286 15 9.29289 15.1464 9.14645C15.2929 9 15.5286 9 16 9C16.4714 9 16.7071 9 16.8536 9.14645C17 9.29289 17 9.5286 17 10C17 10.4714 17 10.7071 16.8536 10.8536C16.7071 11 16.4714 11 16 11C15.5286 11 15.2929 11 15.1464 10.8536C15 10.7071 15 10.4714 15 10Z");
}

.oazq83bmy {
  d: path("M16 11V12.0296C16 12.9044 15.4315 13.6777 14.5966 13.9386L13.1931 14.3772C12.4833 14.599 12 15.2563 12 16");
}

.p_qjaxbml {
  stroke-linejoin: round;
  d: path("M12 16V14.125V6M11 7L12 6L13 7");
}

.r_3lljbpa {
  d: path("M8 10V11.0296C8 11.9044 8.5685 12.6777 9.40345 12.9386L10.8069 13.3772C11.5167 13.599 12 14.2563 12 15");
}

</style>
