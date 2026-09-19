<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ih3htmbgg"/><path class="adv24eb1y"/><path class="hl0mocbwm"/><circle class="u7z632bne"/><path class="yn48qywch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obsidentify" /></template>
<style>
.adv24eb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.444 25.643c8.054-9.028-2.945-18.878-11.635-8.388c-.913-2.055-2.086-2.957-3.809-3.063c-1.723.106-2.896 1.008-3.808 3.063c-9.66-11.66-22.17 1.809-8.203 11.346c-7.883 8.293.522 16.676 8.947 8.76c.522.87 1.405 1.8 3.064 1.795c1.66.006 2.542-.926 3.064-1.794");
}

.hl0mocbwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.197 14.428c.633-5.072 4.35-7.53 7.081-7.191");
}

.ih3htmbgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.803 14.428c-.633-5.072-4.35-7.53-7.081-7.191");
}

.u7z632bne {
  cx: 34.931px;
  cy: 33.279px;
  r: 8.869px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yn48qywch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.859 31.008l-5.132 5.131l-2.774-2.773");
}

</style>
