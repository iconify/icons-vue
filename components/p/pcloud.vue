<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ms4i5wbmy"/><path class="pcu5d6u_z"/><path class="ob32sq3az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pcloud" /></template>
<style>
.ms4i5wbmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.05 24.174c.192-6.69-5.076-12.27-11.767-12.463s-12.27 5.076-12.463 11.767a12 12 0 0 0 0 .696");
}

.ob32sq3az {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.24 30.044v-10.74h3.49a3.63 3.63 0 0 1 0 7.25h-3.49");
}

.pcu5d6u_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.242 18.115a9.1 9.1 0 0 0 .358 18.18h24a5.84 5.84 0 0 0 3.48-10.53h.05a6 6 0 0 0 .24-1.59a5.85 5.85 0 0 0-5.85-5.85q-.377.01-.75.063");
}

</style>
