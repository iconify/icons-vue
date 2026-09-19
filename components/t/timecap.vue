<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="od7ixls0z"/><path class="hilcnhbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:timecap" /></template>
<style>
.hilcnhbxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.248 21.026L9.872 34.344c-2.71 3.85.043 9.156 4.752 9.156h18.752c4.709 0 7.462-5.306 4.752-9.156l-9.376-13.318c-2.315-3.288-7.189-3.288-9.504 0");
}

.od7ixls0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.248 26.974L9.872 13.657c-2.71-3.85.043-9.157 4.752-9.157h18.752c4.709 0 7.462 5.307 4.752 9.157l-9.376 13.317c-2.315 3.288-7.189 3.288-9.504 0");
}

</style>
