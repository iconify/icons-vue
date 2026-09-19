<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h57zgdbru"/><path class="zceiobbfc"/><path class="ywamjmb_b"/><circle class="psznu452q"/><path class="y0n-k0qev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:remote-support" /></template>
<style>
.h57zgdbru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.525 39.76c.632.06 1.265.097 1.909.097C35.134 39.857 43 31.98 43 22.28S35.135 4.713 25.434 4.713S7.868 12.578 7.868 22.279c0 .985.085 1.945.243 2.88");
}

.psznu452q {
  cx: 15.62px;
  cy: 32.667px;
  r: 10.62px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y0n-k0qev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.25 30.829a5.636 5.636 0 0 0-11.271 0v2.258m1.845 2.258v-4.517m9.426.001v2.258m-1.845 2.258v-4.517m-2.661 8.552c4.577 0 4.507-2.475 4.507-6.293");
}

.ywamjmb_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.381 8.539l-.837 3.889l-4.015 1.993");
}

.zceiobbfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.224 32.186a9.93 9.93 0 0 0 9.154-9.907a9.94 9.94 0 0 0-9.944-9.944c-5.422 0-9.823 4.327-9.944 9.713");
}

</style>
