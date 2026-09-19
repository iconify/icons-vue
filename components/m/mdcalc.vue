<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_l3gxlof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mdcalc" /></template>
<style>
.o_l3gxlof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.313 5.5a2.556 2.556 0 0 0-2.56 2.563v9.69h-9.69a2.556 2.556 0 0 0-2.563 2.56v7.373a2.556 2.556 0 0 0 2.563 2.561h9.69v9.69a2.556 2.556 0 0 0 2.56 2.563h7.374c1.42 0 2.56-1.144 2.56-2.563v-9.69h9.69a2.556 2.556 0 0 0 2.563-2.56v-7.374c0-1.42-1.144-2.56-2.563-2.56h-9.69v-9.69a2.556 2.556 0 0 0-2.56-2.563z");
}

</style>
