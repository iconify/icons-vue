<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ckmlpgblh"/><path class="vibnpjb-f"/></g><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oasth-bus" /></template>
<style>
.ckmlpgblh {
  d: path("M30.919 7.922a17.3 17.3 0 0 0-6.836-1.433a17.4 17.4 0 0 0-6.838 1.433l6.816 15.96l-6.826 16.19a17.35 17.35 0 0 0 6.848 1.44a17.3 17.3 0 0 0 6.846-1.44");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vibnpjb-f {
  d: path("M41.543 23.999L27.43 23.89M33.4 9.913c4.858 2.826 8.142 8.092 8.143 14.086c0 5.994-3.278 11.256-8.128 14.085c0 0-5.996-9.059-5.984-14.193c.011-5.066 5.969-13.978 5.969-13.978M6.453 23.84l14.031-.107m-4.456 10.57l4.456-10.57l-5.935-13.9c-4.831 2.81-8.096 8.046-8.096 14.006a16.12 16.12 0 0 0 3.854 10.464");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
