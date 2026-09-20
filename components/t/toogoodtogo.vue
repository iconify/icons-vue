<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afp27wz0o"/><path class="yr909420c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toogoodtogo" /></template>
<style>
.afp27wz0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9zc2.63 0 5.15 1.8 7 5a24.65 24.65 0 0 1 2.9 12.09c0 9.43-4.43 17.08-9.9 17.08s-9.9-7.65-9.9-17.08S18.52 9 24 9");
}

.yr909420c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.4 42c-3.51-.86-7.21-3.76-9.91-6.87C4.32 28 2.64 19.34 6.75 15.77a6.7 6.7 0 0 1 4.42-1.52a13.7 13.7 0 0 1 5.1 1.12m15.46-.01a13.7 13.7 0 0 1 5.1-1.12a6.7 6.7 0 0 1 4.42 1.52c4.11 3.57 2.43 12.22-3.74 19.34c-2.7 3.11-6.4 6-9.91 6.87");
}

</style>
