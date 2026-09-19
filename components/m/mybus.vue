<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wkg8csx3e"/><circle class="g0ov83bnq"/><circle class="ca0bdm21d"/><path class="o_xl2760h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mybus" /></template>
<style>
.ca0bdm21d {
  cx: 33.909px;
  cy: 30.927px;
  r: 2.251px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g0ov83bnq {
  cx: 14.088px;
  cy: 30.927px;
  r: 2.251px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o_xl2760h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.568 9.44h12.731M12.058 23.4h23.647l-1.393-11.19H13.625z");
}

.wkg8csx3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.955 5.502c-7.586 0-13.812 2.968-14.089 6.716h-.009L8.795 37.756h2.944a2 2 0 0 0-.007.184v2.647c0 1.058.85 1.913 1.913 1.913h.85a1.91 1.91 0 0 0 1.914-1.913v-2.651q0-.092-.01-.185h15.21q-.009.092-.009.185v2.642a1.91 1.91 0 0 0 1.913 1.915h.85a1.91 1.91 0 0 0 1.914-1.915v-2.642q0-.092-.01-.185h2.938l-1.161-25.663h-.014C37.62 8.392 31.44 5.5 23.955 5.5z");
}

</style>
