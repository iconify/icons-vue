<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq9xq2sid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tv-guide" /></template>
<style>
.oq9xq2sid {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zm3.346-4.962h1V9.962h2.173L14 15.038h1.077l2.27-6.077h-1.155L14.54 13.52l-1.616-4.558h-6.5v1h2.539z");
}

</style>
