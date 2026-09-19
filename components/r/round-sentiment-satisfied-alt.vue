<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mmn7xsb7v"/><circle class="an0_1xo_x"/><path class="t-b4dfb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-sentiment-satisfied-alt" /></template>
<style>
.an0_1xo_x {
  cx: 8.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.mmn7xsb7v {
  cx: 15.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.t-b4dfb5v {
  fill: currentColor;
  d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2M12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8m4.41-6.11a.745.745 0 0 0-1.03.24C14.64 15.3 13.38 16 12 16s-2.64-.7-3.38-1.88a.747.747 0 1 0-1.27.79C8.37 16.54 10.1 17.5 12 17.5s3.63-.97 4.65-2.58c.22-.35.11-.81-.24-1.03");
}

</style>
