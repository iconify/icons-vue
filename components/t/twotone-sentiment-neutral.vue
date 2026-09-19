<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5kanrbuu"/><path class="j5q8dobdr"/><circle class="mmn7xsb7v"/><circle class="an0_1xo_x"/><path class="nqa-9soic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-sentiment-neutral" /></template>
<style>
.an0_1xo_x {
  cx: 8.5px;
  cy: 9.5px;
  r: 1.5px;
  fill: currentColor;
}

.j5q8dobdr {
  fill: currentColor;
  d: path("M9 14h6v1.5H9z");
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

.o5kanrbuu {
  fill: currentColor;
  d: path("M12 4c-4.42 0-8 3.58-8 8s3.58 8 8 8s8-3.58 8-8s-3.58-8-8-8M7 9.5C7 8.67 7.67 8 8.5 8s1.5.67 1.5 1.5S9.33 11 8.5 11S7 10.33 7 9.5m8 6H9V14h6zm.5-4.5c-.83 0-1.5-.67-1.5-1.5S14.67 8 15.5 8s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
