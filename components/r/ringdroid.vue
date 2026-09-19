<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="arect08wk"/><ellipse transform="rotate(-22.54 9.31 38.769)" class="cokizj-9z"/><ellipse transform="rotate(-22.54 31.037 33.68)" class="tnwo29aiy"/><path class="ynbytjbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ringdroid" /></template>
<style>
.arect08wk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.86 32.68v-9h-7.69l15.33-5.85l-7.64.07V5.75l-21.75 5.06v11.46l7.65-.14l-15.33 5.54l7.68-.05v10.21");
}

.cokizj-9z {
  cx: 9.31px;
  cy: 38.77px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.04px;
  ry: 3.14px;
}

.tnwo29aiy {
  cx: 31.05px;
  cy: 33.69px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.04px;
  ry: 3.14px;
}

.ynbytjbng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.11 14.4l21.75-5.06");
}

</style>
