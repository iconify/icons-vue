<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ix120xbln"/><path class="ygphpyblj"/><ellipse class="xbmghqbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trofasade24" /></template>
<style>
.ix120xbln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.176 20.11l12.04-12.52l-7.356 13.216m-4.684-.696L10.154 5.5l11.502 15.24m7.248 6.795l10.032 9.505l-6.516-12.664m-7.686 4.051L9.499 39.987L21.48 24.882");
}

.xbmghqbkm {
  cx: 26.781px;
  cy: 12.287px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.802px;
  ry: 2.709px;
}

.ygphpyblj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.626 42.5l3.838-17.522L42.33 22.36l-15.153-2.25L5.67 22.564l18.868 2.766z");
}

</style>
