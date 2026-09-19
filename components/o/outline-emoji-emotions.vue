<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mmn7xsb7v"/><circle class="an0_1xo_x"/><path class="j-4ka7bds"/><path class="nqa-9soic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-emoji-emotions" /></template>
<style>
.an0_1xo_x {
  cx: 8.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.j-4ka7bds {
  fill: currentColor;
  d: path("M12 18c2.28 0 4.22-1.66 5-4H7c.78 2.34 2.72 4 5 4");
}

.mmn7xsb7v {
  cx: 15.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.nqa-9soic {
  fill: currentColor;
  d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2M12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8");
}

</style>
