<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="p0cznvblv"/><path class="ydmy7ntjv"/><path class="hh0t8fd3o"/></g><path class="qt4w5c6db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallipop" /></template>
<style>
.hh0t8fd3o {
  d: path("M17.217 5.592A19.8 19.8 0 0 0 5.5 16.794m37 .856A19.8 19.8 0 0 0 30.443 5.587");
  opacity: var(--svg-opacity--0-965, 0.965);
}

.p0cznvblv {
  d: path("M24.437 14.972a7.98 7.98 0 0 0-7.655 5.722c2.574 2.187 7.761 7.643 7.761 7.643l2.775-2.937s2.6-1.767 4.765-.185a7.973 7.973 0 0 0-7.647-10.243z");
}

.qt4w5c6db {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.512 26.04l5.602-5.677s2.889-1.934 5.319.03s8.11 7.944 8.11 7.944l2.775-2.936s2.798-1.912 5.004-.008c2.207 1.905 10.008 9.76 10.008 9.76m-17.787-6.816L10.245 42.414");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ydmy7ntjv {
  d: path("M24.119 9.932a13.424 13.424 0 0 0-13.057 10.482l.051-.052s2.89-1.934 5.32.03s8.11 7.945 8.11 7.945l2.775-2.937s2.799-1.911 5.005-.007c.784.677 2.305 2.146 3.901 3.707a13.4 13.4 0 0 0 1.319-5.745c0-7.413-6.01-13.423-13.424-13.423");
}

</style>
