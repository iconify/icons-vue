<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_pu4x-lq"/><circle class="y6kix7fzy"/><path class="iynnt8bqt"/><circle class="de7ap_b8n"/><path class="fp-drib9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tuttoandroid" /></template>
<style>
.de7ap_b8n {
  cx: 32.002px;
  cy: 17.031px;
  r: 2.545px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fp-drib9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.73 27.387c-2.334-1.55-10.55 3.773-11.366 10.645c-.6 5.062 6.052 6.003 8.124 3.822c2.473-2.601 5.443-13.006 3.242-14.467m-3.319.313H7.589");
}

.g_pu4x-lq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.342 42.05c-2.85 1.29-6.14 2.02-9.64 2.02H23.7c-3.5 0-6.79-.73-9.64-2.02M12.04 5.043l3.097 4.856");
}

.iynnt8bqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.27 27.387c2.334-1.55 10.55 3.773 11.366 10.645c.6 5.062-6.052 6.003-8.124 3.822c-2.473-2.601-5.443-13.006-3.242-14.467m38.69-2.361c0-9.449-8.488-17.108-18.96-17.108S5.04 15.578 5.04 25.026zM35.961 5.043l-3.098 4.856");
}

.y6kix7fzy {
  cx: 15.998px;
  cy: 17.031px;
  r: 2.545px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
