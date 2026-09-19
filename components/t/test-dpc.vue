<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a2nk42b-y"/><path class="ptnk31uwf"/><path class="tcjq3tb0z"/><path class="hcv2-hwpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:test-dpc" /></template>
<style>
.a2nk42b-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.829 14.197v19.606L24 44.5L6.172 33.803V14.197L24 3.5z");
}

.hcv2-hwpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.887 21.882c-.539-4.24 4.765-4.24 4.226 0M24 23.995c.875 0 1.588.713 1.588 1.588s-.713 1.589-1.588 1.589s-1.588-.714-1.588-1.589s.713-1.588 1.588-1.588");
}

.ptnk31uwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 34.063l8.863-5.275v-9.576L24 13.937l-8.863 5.275v9.576zm8.909-14.817l8.92 5.343m-26.432 14.67L24 34.063m-8.863-14.885V8.843");
}

.tcjq3tb0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.76 28.235v-5.304q0-1.05 1.063-1.05h6.273q1.144 0 1.144 1.05v5.304q0 1.065-1.063 1.064h-6.354q-1.063 0-1.063-1.064");
}

</style>
