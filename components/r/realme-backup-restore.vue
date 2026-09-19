<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bb4rj1b1x"/><path class="o2j25nbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:realme-backup-restore" /></template>
<style>
.bb4rj1b1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.134 9.257h10.692a2.676 2.676 0 0 1 2.674 2.675v24.13a2.68 2.68 0 0 1-2.68 2.68H29.127a2.676 2.676 0 0 1-2.675-2.674v-24.13a2.68 2.68 0 0 1 2.68-2.68M8.18 9.257h10.692a2.676 2.676 0 0 1 2.675 2.675v24.13c0 1.48-1.202 2.68-2.68 2.68H8.173A2.676 2.676 0 0 1 5.5 36.069v-24.13a2.68 2.68 0 0 1 2.68-2.68");
}

.o2j25nbvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.523 26.933H29.85v3.788L36.673 24l-6.823-6.923v3.621H13.523z");
}

</style>
