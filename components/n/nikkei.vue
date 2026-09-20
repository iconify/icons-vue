<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="hexzgdclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nikkei" /></template>
<style>
.hexzgdclf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.808 20.658l-1.813 6.65m-5.013-3.325h2.199m.277 3.326h-3.383l1.813-6.65h3.383m-7.714 6.683l-1.876-3.325m-1.129 1.009l4.812-4.312m-3.631-.023l-1.813 6.65m-2.531-.021l-1.876-3.325m-1.129 1.008l4.812-4.312m-3.631-.022l-1.812 6.651m-.722-6.662l-1.813 6.65m-7.019.001l1.813-6.65l2.67 6.65l1.812-6.65");
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
