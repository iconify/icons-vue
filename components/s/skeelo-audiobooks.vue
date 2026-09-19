<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q29dpmqxg"/><circle class="bc9ii1m5h"/><path class="pnbv9jbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skeelo-audiobooks" /></template>
<style>
.bc9ii1m5h {
  cx: 16.079px;
  cy: 17.322px;
  r: 4.452px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pnbv9jbaq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.124 41.865a8.96 8.96 0 0 0 4.04-7.034c0-5.911-5.35-6.323-5.35-14.441c-1.87-1.61-6.532-9.551-4.152-14.03c.636-1.197 8.455 2.956 8.455 2.956c4.452-2.245 5.65-3.18 11.71-3.18S43 11.71 43 17.023c0 10.7-8.792 9.428-12.496 16.536a19.04 19.04 0 0 0-1.758 8.306Zm3.868-28.857l-.875-3.693");
}

.q29dpmqxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.994 18.407c1.983-3.405 5.612-4.527 10.027-2.956c-1.983 4.04-6.622 5.388-10.027 2.956");
}

</style>
