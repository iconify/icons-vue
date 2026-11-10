<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n2ky8ee1l"/><path class="t0oef-vwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ubs-access" /></template>
<style>
.n2ky8ee1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.636 19.665a7.582 7.582 0 1 0-7.582-7.583");
}

.t0oef-vwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.081 12.485a7.582 7.582 0 0 0-10.027 7.18c0 3.209 2 5.937 4.817 7.044v13.009l2.765 3.782l2.765-3.782v-13.01c2.817-1.106 4.817-3.834 4.817-7.043a7.56 7.56 0 0 0-1.015-3.794M18.144 26.246l-5.643 5.643l-.719 4.63l4.63-.719l5.642-5.643");
}

</style>
