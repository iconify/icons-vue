<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nlzikabed"/><path class="s7-uz_b_o"/><path class="hyitxfbfx"/><path class="srvck0-gr"/><path class="tro9b3bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nethack" /></template>
<style>
.hyitxfbfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.072c-7.342-3.703-13.587-14.535-13.587-14.535V5.928l3.703 3.703l3.675-3.675H30.21l3.675 3.675l3.703-3.703v21.609S31.342 38.369 24 42.072");
}

.nlzikabed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.587 14.55a12.35 12.35 0 0 0 5.913-.885L39.41 8.36l-1.823 1.05m-2.021 21.26a13.6 13.6 0 0 0 5.502 5.101l-3.095 1.659s.443 2.708 1.603 3.648c-3.537.607-7.375-.757-8.44-4.8");
}

.s7-uz_b_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.495 32.167s1.765 1.283.66 2.223a1.886 1.886 0 0 1-2.34-.06");
}

.srvck0-gr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.413 14.55a12.35 12.35 0 0 1-5.913-.885L8.59 8.36l1.824 1.05m2.02 21.26a13.6 13.6 0 0 1-5.502 5.101l3.095 1.659s-.443 2.708-1.603 3.648c3.537.607 7.375-.757 8.44-4.8");
}

.tro9b3bjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.505 32.167s-1.765 1.283-.66 2.223a1.886 1.886 0 0 0 2.34-.06M24 5.956v36.116");
}

</style>
