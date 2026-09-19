<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pq5ryfoep"/><path class="ogd8upbiy"/><circle class="vrg0izt_i"/><path class="g0n4x6b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paypal-business" /></template>
<style>
.g0n4x6b3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.632 10.394a1.951 1.951 0 1 1 0 3.903h-3.22V6.492h3.22a1.951 1.951 0 1 1 0 3.902m0 0h-3.219");
}

.ogd8upbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.42 16.29c1.16 1.71 1.35 4.01.83 6.71c-1.4 7.18-6.18 9.67-12.29 9.67H27c-.76.01-1.4.58-1.49 1.33l-.07.41l-1.19 7.49l-.06.32c-.12.74-.75 1.28-1.5 1.28h-6.31c-.78.06-1.46-.52-1.52-1.29V42c.15-.95.3-1.89.44-2.83H8.52c-.55.01-1.01-.43-1.02-.98c0-.07.01-.15.02-.22l5-32c.13-.85.87-1.48 1.73-1.47h12.12c1.79 0 3.41.16 4.82.51");
}

.pq5ryfoep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.6 17.32c-2.08 6.55-7.16 8.88-13.52 8.88h-4.24c-.5-.05-1-.03-1.49.06c-.03.17-.05.34-.08.5c-.16 1.04-.32 2.07-.49 3.08c-.02.13-.04.26-.06.38c-.22 1.44-.45 2.88-.68 4.32c-.24 1.51-.48 3.02-.72 4.52v.11h-.02c.01-.03.01-.06.02-.09v-.02c.24-1.5.48-3.01.72-4.52c.23-1.44.46-2.88.68-4.32c.02-.12.04-.25.06-.38c.17-1.02.33-2.05.49-3.08c.03-.16.05-.33.08-.5c.62-3.93 1.24-7.87 1.86-11.81a1.52 1.52 0 0 1 1.5-1.28h8.52");
}

.vrg0izt_i {
  cx: 35.662px;
  cy: 10.394px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
