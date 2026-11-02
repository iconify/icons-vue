<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le_axno5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plane-takeoff-fill" /></template>
<style>
.le_axno5j {
  fill: currentColor;
  d: path("m17.707 8.707l-1.636 1.636l.831 4.985a2 2 0 0 1-.559 1.743l-.136.136a1.614 1.614 0 0 1-2.431-.173l-2.075-2.766l-.701.35v.968A2 2 0 0 1 10.414 17l-.207.207a1.706 1.706 0 0 1-2.414 0l-3-3a1.706 1.706 0 0 1 0-2.414L5 11.586A2 2 0 0 1 6.414 11h.968l.35-.701l-2.766-2.075a1.615 1.615 0 0 1-.173-2.431l.136-.136a2 2 0 0 1 1.743-.559l4.985.831l1.636-1.636c.77-.771 1.784-1.678 2.886-1.899c.99-.197 1.836.207 2.528.899c1.951 1.952.536 3.878-1 5.414M21 20a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
