<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o18y51b7b"/><path class="mw_7efb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spaarkoning" /></template>
<style>
.mw_7efb_f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.982 19.908l-7.194-8.441a1.03 1.03 0 0 0-1.571.003l-7.154 8.464");
}

.o18y51b7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.708 36.895H39.07m.79-4.589l3.608-16.566c.247-1.135-.976-2.02-1.977-1.431l-17.49 10.298L6.508 14.31c-1.001-.59-2.224.296-1.977 1.43L8.14 32.307z");
}

</style>
