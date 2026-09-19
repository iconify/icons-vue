<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhcp778_b"/><path class="vi755jb5s"/><path class="ot_a-qbyq"/><path class="l-czezb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sncf" /></template>
<style>
.bhcp778_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 13.9v20.3h35.2l3.8-11.9C31.3 14 17.9 14 4.7 13.9Z");
}

.l-czezb1a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.9 30.4c.2 0 1.2-5.3 1.7-8c.2 0 6.6 0 6.7.1m-7.5 4h5.3");
}

.ot_a-qbyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.6 22.6c-8.8-.7-8.7 9.3.3 7.8");
}

.vi755jb5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 30.1c2.4 1.2 7.9.4 7.9-2.1c.1-2.2-5.5-1.3-5.5-3.4c-.1-1.4 2.6-2.7 6.1-2m.6 3.9c.1-.1.5-2.5.8-3.6c3.3 1.1 5.1 7.6 5.7 7.6c.6-2.8 1.7-8.2 1.7-8.5");
}

</style>
