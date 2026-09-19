<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="j4aqaow3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:milkrun" /></template>
<style>
.j4aqaow3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.492 21.228v5.543h2.771m-4.659-5.543v5.543m-7.43-.006v-5.537l2.771 5.543l2.771-5.534v5.534m13.302-.001v-5.542h1.814c1.026 0 1.857.834 1.857 1.862s-.831 1.86-1.857 1.86h-1.814m1.815.001l1.815 1.818m7.488.002v-5.543l3.672 5.543v-5.543m-19.657 0v5.543m2.979 0L21.851 24l2.279-2.753M21.851 24h-.7m10.426-2.772v3.707a1.836 1.836 0 1 0 3.672 0v-3.707");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
