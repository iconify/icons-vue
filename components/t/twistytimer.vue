<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-75 24 24)" class="kw8-8wbhh"/><rect transform="rotate(-75 24.01 24.19)" class="dl_d1h6ok"/><path class="mkk_dmoxt"/><path class="e3hkf4b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:twistytimer" /></template>
<style>
.dl_d1h6ok {
  width: 6.638px;
  height: 6.638px;
  x: 20.691px;
  y: 20.871px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.161px;
}

.e3hkf4b8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.472 32.914l17.266 4.626a3.758 3.758 0 0 0 5.096-2.856m-22.362-1.77s-2.95 7.245 5.641 9.547m14.133-26.046s.96-7.317-5.2-8.967");
}

.kw8-8wbhh {
  width: 36.126px;
  height: 36.126px;
  x: 5.937px;
  y: 5.937px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.227px;
}

.mkk_dmoxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.039 38.537l6.455-24.091a3.478 3.478 0 0 1 4.566-2.636l17.186 4.605l-3.488 13.014c-.118.442 7.024 1.72 8.852-5.11");
}

</style>
