<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="smf4xeb7t"/><path class="k4-kufbww"/><path class="hkag89buj"/><path class="ohfi8cbpy"/></g><path class="x5_480mtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:recipe-keeper" /></template>
<style>
.hkag89buj {
  d: path("M15.51 24.468c.288-2.594 3.296-5.514 14.772-9.019");
}

.k4-kufbww {
  d: path("M10.884 26.574c0 6.792 7.628 11.804 7.628 11.804M24 24.468h18.5c0 9.216-11.597 17.14-11.597 17.14H24m-9.906-17.14c-1.346-5.039 7.654-8.503 15.73-9.573l.79-1.454l3.184 3.87l-1.747.284c-.855 2.81-5.135 6.873-5.135 6.873");
}

.ohfi8cbpy {
  d: path("M30.578 15.81c-4.34 2.174-9.4 4.672-12.946 8.658m13.793-7.631C26.915 22.963 24 24.468 24 24.468m-2.495 0c2.72-1.59 9.49-8.154 9.49-8.154m2.082.139l8.151-6.605a1.311 1.311 0 1 0-1.652-2.038l-8.15 6.605");
}

.smf4xeb7t {
  d: path("M24 24.468H5.5c0 9.216 11.597 17.14 11.597 17.14H24");
}

.x5_480mtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.825 14.895l2.226 2.7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
