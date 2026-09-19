<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="megb5cobo"/><path class="xs9zgtg0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reon-pocket" /></template>
<style>
.megb5cobo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5a21.5 21.5 0 0 0-5.889.864c-1.06.31-2.008 1.537-2.134 2.635c-.637 5.568-.973 11.733-.977 18c.004 6.269.34 12.434.977 18.002c.126 1.097 1.075 2.325 2.134 2.635A21.5 21.5 0 0 0 24 45.5a21.5 21.5 0 0 0 5.889-.864c1.06-.31 2.008-1.538 2.134-2.635c.637-5.569.973-11.733.977-18.001c0-6.282-.334-12.463-.97-18.048c-.126-1.098-1.076-2.32-2.137-2.624A21.5 21.5 0 0 0 24 2.5");
}

.xs9zgtg0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.815 39.973a19.5 19.5 0 0 1-7.413-21.837A19.5 19.5 0 0 1 15.948 6.24m16.116.006a19.5 19.5 0 0 1 10.533 11.89a19.5 19.5 0 0 1-7.412 21.838");
}

</style>
