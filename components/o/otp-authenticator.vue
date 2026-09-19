<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i8d7e7bmu"/><circle class="gwobo9b1h"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:otp-authenticator" /></template>
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

.gwobo9b1h {
  cx: 17.498px;
  cy: 17.337px;
  r: 2.288px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i8d7e7bmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.83 26.342a7.836 7.836 0 0 1-9.498-2.61a7.276 7.276 0 0 1 .982-9.516a7.88 7.88 0 0 1 9.845-.736a7.31 7.31 0 0 1 2.479 9.257m-3.702 3.607l4.082 4.083h2.295v2.19h2.241v2.248l1.04 1.041H36v-3.278l-9.503-9.503");
}

</style>
