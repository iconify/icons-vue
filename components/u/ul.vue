<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iw6b3io2g"/><path class="eywf4ljxn"/><circle class="jjfinzbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ul" /></template>
<style>
.eywf4ljxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.007 15.19v17.62h8.615M10.378 15.19v11.784c0 3.224 2.555 5.837 5.707 5.837s5.707-2.613 5.707-5.837V15.19");
}

.iw6b3io2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.088 41.057c-8.987 6.896-21.784 5.636-29.253-2.881s-7.049-21.369.962-29.38c8.01-8.01 20.862-8.43 29.379-.96c8.517 7.468 9.777 20.265 2.881 29.252");
}

.jjfinzbny {
  cx: 39.203px;
  cy: 39.203px;
  r: 0.75px;
  fill: currentColor;
}

</style>
