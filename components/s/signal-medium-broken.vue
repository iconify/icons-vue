<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2aqw9y_p"/><path class="ty65c8klf"/><path class="p7wskfbnq"/><path class="s7tkw_jdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:signal-medium-broken" /></template>
<style>
.a2aqw9y_p {
  d: path("M3 20H3.0001");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7wskfbnq {
  d: path("M12 20V17");
}

.s7tkw_jdb {
  d: path("M12 14V12");
}

.ty65c8klf {
  d: path("M7.5 20V16");
}

</style>
