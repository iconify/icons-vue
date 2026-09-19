<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="k6_0lbdph"/><path class="a56mlhbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:walli" /></template>
<style>
.a56mlhbab {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.616 32.703c.8-1.3.8-2.998 0-4.397l-7.594-13.09c-1.3-2.199-4.098-2.898-6.296-1.7c-.8.5-1.399 1.2-1.799 2c-.6 1.298-.6 2.797.2 4.196l7.495 13.09c1.3 2.2 4.097 2.899 6.296 1.7c.799-.5 1.399-1.1 1.698-1.799m14.89 0c.8-1.3.8-2.998 0-4.397l-7.495-13.09c-1.3-2.199-4.097-2.898-6.296-1.7c-.799.5-1.399 1.2-1.798 2c-.6 1.298-.6 2.797.2 4.196l7.494 13.09c1.3 2.2 4.097 2.899 6.296 1.7c.7-.5 1.299-1.1 1.599-1.799");
}

.k6_0lbdph {
  cx: 38.903px;
  cy: 17.514px;
  r: 4.597px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
