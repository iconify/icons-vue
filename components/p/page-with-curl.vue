<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ep8s8mqkt"/><path class="i_738u7bg"/><path class="mepx9va1f"/><path class="o-y_hyb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:page-with-curl" /></template>
<style>
.ep8s8mqkt {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M9.42 102.85V6.51a3.06 3.06 0 0 1 3.06-3.06h89.11a3.06 3.06 0 0 1 3.06 3.06v118.04H31.12c-11.98 0-21.7-9.71-21.7-21.7");
}

.i_738u7bg {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M104.65 103.5v21.05c6.98 0 12.77-7.56 13.91-17.48c.22-1.9-1.28-3.57-3.19-3.57zm-63.38 0c-1.96 0-3.6 1.48-3.81 3.43c-1.04 9.42-6.27 16.73-12.75 17.53v.09h79.94V103.5z");
}

.mepx9va1f {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M24.71 103.5H9.42c0 11.63 6.32 21.05 14.11 21.05c.4 0 .79-.04 1.18-.09c7.24-.9 12.93-9.93 12.93-20.96z");
}

.o-y_hyb3w {
  fill: none;
  stroke: var(--svg-color--616161, #616161);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M22.83 29.78h68.34M22.83 45.03h68.34M22.83 60.29h68.34M22.83 75.55h68.34M22.83 90.81h29.23");
}

</style>
