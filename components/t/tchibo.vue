<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-uq_zbsg"/><path class="d8a3jddaj"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tchibo" /></template>
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

.d8a3jddaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.022 8.002c5.152 6.98-14.274 4.546-14.205 8.558c.116 6.754 21.494-5.664 25.466-.132c1.894 2.637 2.131 9.117-13.117 9.542");
}

.p-uq_zbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.96 29.331c-.96 3.962-4.077 7.634-7.202 8.487s-5.238-1.393-4.882-5.19c.355-3.797 3.062-7.903 6.256-9.49s5.83-.136 6.093 3.354");
}

</style>
