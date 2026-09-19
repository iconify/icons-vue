<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u1au89h-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shein" /></template>
<style>
.u1au89h-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.553 39.113c2.44 2.924 5.37 4.387 9.763 4.387h5.857c5.37 0 9.762-4.387 9.762-9.75S32.542 24 27.173 24h-6.345c-5.37 0-9.763-4.387-9.763-9.75s4.393-9.75 9.763-9.75h5.857c4.393 0 7.321.975 9.762 4.388");
}

</style>
