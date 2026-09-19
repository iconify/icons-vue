<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s1b__cczf"/><path class="aua5w5bio"/><path class="fjzjgqbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polaris-office" /></template>
<style>
.aua5w5bio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.914 40.11L9.707 13.694l6.238 2.326");
}

.fjzjgqbrg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.703 12.897L16.216 9.68l-1.302 30.43m10.849-25.385l14.32 6.671M24.57 18.784l14.337 5.74m-15.531-1.681l14.356 4.809m-15.549-.75l14.374 3.878");
}

.s1b__cczf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.136 7.89L43.5 18.739L35.472 40.11H14.914zm-9.222 32.22L4.5 18.955l6.606 1.836");
}

</style>
