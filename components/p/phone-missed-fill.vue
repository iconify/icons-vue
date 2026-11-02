<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq9pbbc6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-missed-fill" /></template>
<style>
.uq9pbbc6l {
  fill: currentColor;
  d: path("m18 4.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L19.414 6l2.293 2.293a.999.999 0 1 1-1.414 1.414L18 7.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L16.586 6l-2.293-2.293a.999.999 0 1 1 1.414-1.414ZM5 2h3c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l1 3c.366 1.101-.505 2.286-1.242 3.023l-1 1a.414.414 0 0 0 0 .586l3 3a.414.414 0 0 0 .586 0l1-1c.737-.737 1.922-1.608 3.023-1.242l3 1c.586.196 1.031.66 1.302 1.203c.271.541.382 1.145.382 1.746v3c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

</style>
