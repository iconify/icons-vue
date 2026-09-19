<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j84kc2bxj"/><path class="zi-j6yp-h"/><path class="yh9mkfb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nubank-new" /></template>
<style>
.j84kc2bxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 33.964v-11.54a6.823 6.823 0 0 1 13.644 0v11.54");
}

.yh9mkfb7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 14.036h-4.525v13.803a6.823 6.823 0 0 1-13.645 0V14.036h4.526");
}

.zi-j6yp-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 33.964h4.526V20.161a6.823 6.823 0 0 1 13.644 0v13.803h-4.526M43.5 14.036v11.54a6.823 6.823 0 0 1-13.644 0v-11.54");
}

</style>
