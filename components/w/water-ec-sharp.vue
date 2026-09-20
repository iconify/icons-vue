<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll0rx_b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:water-ec-sharp" /></template>
<style>
.ll0rx_b6w {
  fill: currentColor;
  d: path("M11 18h1l4-6h-3V8h-1l-4 6h3zm-4.712 1.65Q4 17.3 4 13.8q0-2.5 1.988-5.437T12 2q4.025 3.425 6.013 6.363T20 13.8q0 3.5-2.287 5.85T12 22t-5.712-2.35");
}

</style>
