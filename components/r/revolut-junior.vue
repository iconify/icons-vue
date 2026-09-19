<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gtux8y-da"/><path class="df_1nqm2c"/><circle class="x-etxdbur"/><path class="ohlmi6b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:revolut-junior" /></template>
<style>
.df_1nqm2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.7 15.34c.51 6.07-4.21 11.3-10.15 11.6L38.76 42.5h-8.19L19.39 26.98c-.03-.08-.05-.16-.08-.25v-5.29c0-.23.19-.42.42-.42h6.45c1.02 0 2.04-.26 2.88-.85c1.34-.96 2.08-2.44 2.05-4.03c-.05-2.58-2.27-4.69-4.95-4.69H9.24V5.5h17.45c1.6 0 3.15.34 4.55.95");
}

.gtux8y-da {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.237 14.631h6.892V42.5H9.237z");
}

.ohlmi6b_c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.274 4.857v6a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2v-.664");
}

.x-etxdbur {
  cx: 37.274px;
  cy: 8.857px;
  r: 6.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
