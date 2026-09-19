<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="gm6iqnboc"/><path class="qxstki-aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sns-mobiel-bankieren" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gm6iqnboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.565 3.233l1.418 16.736l13.785 9.596l-16.736 1.417l-9.596 13.785l-1.418-16.736l-13.785-9.596l16.736-1.417z");
}

.qxstki-aj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.202 8.797l-8.22 11.172l13.785-1.533m-5.565 20.768l-11.171-8.221l1.532 13.785M8.798 39.204l8.22-11.172l-13.785 1.534M8.798 8.797l11.17 8.22l-1.534-13.784m11.131 0L18.436 44.768m26.331-15.203L3.232 18.436m27.75 1.533l-13.965 8.063m2.952-11.014l8.063 13.965");
}

</style>
