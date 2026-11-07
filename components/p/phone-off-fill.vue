<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pafa5_bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-fill" /></template>
<style>
.pafa5_bum {
  fill: currentColor;
  d: path("m7.706 17.708l-4.999 4.999a.999.999 0 1 1-1.414-1.414l4.999-4.999a16.8 16.8 0 0 1-2.956-4.677A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2h3c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l1 3c.366 1.101-.505 2.286-1.242 3.023l-1 1a.414.414 0 0 0 0 .586l.793.793L21.293 1.293a.999.999 0 1 1 1.414 1.414Zm2.301.528l6.182-6.183c.368-.106.761-.124 1.127-.002l3 1c.586.196 1.031.66 1.302 1.203c.271.541.382 1.145.382 1.746v3c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a17 17 0 0 1-3.097-1.707Z");
}

</style>
