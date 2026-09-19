<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><ellipse transform="rotate(-66.139 26.27 17.415)" class="q8zcryf7r"/><path class="zhf7d1bxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plugshare" /></template>
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

.q8zcryf7r {
  cx: 26.269px;
  cy: 17.415px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.393px;
  ry: 9.901px;
}

.zhf7d1bxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.214 13.41c-3.555 6.427-7.592 11.473-3.471 17.403c-1.64 3.154-1.06 11.47-1.06 11.47M35.324 21.42c-2.95 6.954-4.422 13.473-13.17 14.103c-1.175 2.26-1.21 7.17-1.136 9.772m1.63-31.003l4.479 2.222m-5.52-.125l4.48 2.223m3.89-.994l-1.23 2.24c1.587.84 2.565 1.04 2.986.136s-.442-1.777-1.756-2.376");
}

</style>
