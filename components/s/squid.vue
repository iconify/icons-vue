<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cwbwukbfd"/><path class="arcd9c65e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:squid" /></template>
<style>
.arcd9c65e {
  d: path("m10.11 5.69l-4.4 1.87q-.46.19.03.29l2.77.55q.49.1.72-.34l1.11-2.12q.23-.44-.23-.25m3.78 0l4.4 1.87q.46.19-.03.29l-2.77.55q-.49.1-.72-.34l-1.11-2.12q-.23-.44.23-.25M9.6 15.75v2C9.6 19 8.85 20 8.1 21m3.9-5.25v5.5m2.4-5.5v2c0 1.25.75 2.25 1.5 3.25");
}

.cwbwukbfd {
  d: path("m12.42 3.55l2.16 4.15q.42.8.34 1.7l-.34 3.7q-.08.9-.98.9h-3.2q-.9 0-.98-.9l-.34-3.7q-.08-.9.34-1.7l2.16-4.15q.42-.8.84 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
