<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2rj45lla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:suissemobile" /></template>
<style>
.d2rj45lla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19 5.055h10.293V16.75l10.943-3.488l3.264 9.917l-10.89 3.557l6.942 9.61l-8.412 6.6l-6.977-9.78l-7.215 9.78l-7.934-6.6l6.84-9.61L4.5 23.18l3.386-9.917L19 16.75Z");
}

</style>
