<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2aqw9y_p"/><path class="ty65c8klf"/><path class="ftbpoxdwt"/><path class="hs76-fbie"/><path class="loew5srzp"/><path class="djxvmhcvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-broken" /></template>
<style>
.a2aqw9y_p {
  d: path("M3 20H3.0001");
}

.djxvmhcvj {
  d: path("M21 7V4");
}

.ftbpoxdwt {
  d: path("M12 20V12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs76-fbie {
  d: path("M16.5 20V8");
}

.loew5srzp {
  d: path("M21 20V11");
}

.ty65c8klf {
  d: path("M7.5 20V16");
}

</style>
