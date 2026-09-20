<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zb6vo9c-p"/><path class="ucsncyqqe"/><path class="olxc00wjs"/><path class="zka_zabrc"/><path class="kdybz_aht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:silver-medal-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdybz_aht {
  d: path("M9 17h6");
}

.olxc00wjs {
  d: path("M6 15a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.ucsncyqqe {
  d: path("m17 3 -5 5");
}

.zb6vo9c-p {
  d: path("m7 3 5 5");
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
