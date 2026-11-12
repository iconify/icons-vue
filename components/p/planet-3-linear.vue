<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="l56t-lhik"/><path class="nb8r4hiia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:planet-3-linear" /></template>
<style>
.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l56t-lhik {
  d: path("M21.1713 8.0077H21C21 8.0077 19.0829 7.87028 16.5 8.75575C15.1257 9.22689 13.5 11 10.4372 11C5.93717 11 3 8.0077 3 8.0077L2.87744 7.89777");
}

.nb8r4hiia {
  d: path("M21.6056 14.7907L21.2702 15C19.8904 15.871 17.5211 17 14.5094 17C11.1721 17 9.40075 15.2269 7.90327 14.7558C5.08892 13.8703 3.00004 14.0077 3.00004 14.0077L2.20703 14.0336");
}

</style>
