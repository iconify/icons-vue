<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-9uxoly"/><circle class="an0_1xo_x"/><path class="puymjbb_n"/><circle class="mmn7xsb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mood-bad" /></template>
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

.puymjbb_n {
  fill: currentColor;
  d: path("M11.99 2C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2M12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8m0-6.5c-2.33 0-4.31 1.46-5.11 3.5h10.22c-.8-2.04-2.78-3.5-5.11-3.5");
}

.zd-9uxoly {
  fill: currentColor;
  d: path("M12 4c-4.42 0-8 3.58-8 8s3.58 8 8 8s8-3.58 8-8s-3.58-8-8-8m3.5 4c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-7 0c.83 0 1.5.67 1.5 1.5S9.33 11 8.5 11S7 10.33 7 9.5S7.67 8 8.5 8m-1.61 9c.8-2.04 2.78-3.5 5.11-3.5s4.31 1.46 5.11 3.5z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
