<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b6ocjhr1e"/><g class="y9tr6bcfx"><path class="ybp30rb3a"/><path class="ky6pk8btg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:notebook" /></template>
<style>
.b6ocjhr1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.3 15.172H12.664c-.758 0-1.372.614-1.372 1.372V39.18c0 .758.614 1.372 1.371 1.372H35.3c.757 0 1.372-.614 1.372-1.372V16.544c0-.758-.615-1.372-1.372-1.372");
}

.ky6pk8btg {
  d: path("M17.084 10.39L6.728 11.48c-.753.08-1.3.754-1.22 1.508l2.369 22.511c.08.754.754 1.3 1.508 1.221l1.768-.186m5.381-15.293H31.43m-14.896 4.414H31.43M16.534 30.07H31.43m-14.896 4.414h6.896");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ybp30rb3a {
  d: path("m36.54 34.844l2.08.218a1.37 1.37 0 0 0 1.507-1.221l2.365-22.512a1.37 1.37 0 0 0-1.22-1.508L18.758 7.455a1.37 1.37 0 0 0-1.508 1.221l-.675 6.424");
}

</style>
