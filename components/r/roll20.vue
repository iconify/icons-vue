<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zi974bgym"/><path class="obw9sibik"/><path class="j_s4mcc0e"/><path class="o1vedbc2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:roll20" /></template>
<style>
.j_s4mcc0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.312 32.453H11.688L24 10.585zM24 10.585V2.5m12.312 29.953l6.34 2.297m-30.964-2.297l-6.34 2.297");
}

.o1vedbc2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.643 25.035c0 .827.643 1.47 1.47 1.47s1.47-.643 1.47-1.47v-1.47c0-.827-.643-1.47-1.47-1.47c-.735 0-1.47.643-1.47 1.47zm-4.226-1.47c0-.827.643-1.47 1.47-1.47s1.47.643 1.47 1.47c0 .367-.184.734-.46 1.01c-.643.46-2.48 1.93-2.48 1.93h2.94");
}

.obw9sibik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.312 32.453l6.34-19.203L24 10.585L5.348 13.25l6.34 19.203L24 45.5z");
}

.zi974bgym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.652 34.75v-21.5L24 2.5L5.348 13.25v21.5L24 45.5z");
}

</style>
