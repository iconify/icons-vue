<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gg84aebsp"/><path class="y481nlytz"/><circle class="um_27sbup"/><path class="jnepjhbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-broken" /></template>
<style>
.gg84aebsp {
  stroke-linejoin: round;
  d: path("M5 16.2196C3.14864 14.4047 2 11.8756 2 9.07816C2 6.31313 3.12222 3.8102 4.93603 2M22 9.07816C22 11.836 20.8836 14.333 19.0782 16.1421M19.1414 2.07816C19.9673 2.9206 20.6453 3.90855 21.1334 5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnepjhbrg {
  stroke-linejoin: round;
  d: path("M12.5 11L16 22L12 17.2727M12 17.2727L10.5 15.5M12 17.2727L8 22L11.5 11M12 17.2727L13.5 15.5");
}

.um_27sbup {
  cx: 12px;
  cy: 9.078px;
  r: 2px;
}

.y481nlytz {
  stroke-linejoin: round;
  d: path("M16.2849 5.1221C17.3458 6.13689 18 7.52697 18 9.06033C18 10.6119 17.3302 12.0167 16.2469 13.0345M6 9.06033C6 7.50471 6.67333 6.09655 7.76162 5.07812M7.8 13.0781C7.44967 12.7561 7.14127 12.3941 6.88321 12");
}

</style>
