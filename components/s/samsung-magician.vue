<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="tiwzfkvod"/><path class="jv1o73bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-magician" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jv1o73bhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.037 12.57a11.5 11.5 0 0 0-3.704.27c-6.164 1.471-9.968 7.662-8.495 13.826q.135.566.322 1.105m11.138 7.704a11.5 11.5 0 0 0 3.647-.7c5.951-2.18 9.008-8.77 6.829-14.721a12 12 0 0 0-.45-1.06");
}

.tiwzfkvod {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.82 28.994c.528-1.568.815-3.248.815-4.994c0-8.635-7-15.635-15.635-15.635q-.792 0-1.566.078M8.7 20.765a15.6 15.6 0 0 0-.229 5.055c1.005 8.576 8.772 14.714 17.349 13.709q.787-.093 1.546-.26");
}

</style>
