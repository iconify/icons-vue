<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yowqqmi9x"/><circle class="lvfbl6-sz"/><path class="pbtl-mbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vrsecuregoplus" /></template>
<style>
.lvfbl6-sz {
  cx: 10.293px;
  cy: 31.902px;
  r: 1.49px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pbtl-mbfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.293 33.391v1.766");
}

.yowqqmi9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.463 8.884h13.27l4.234 18.52l3.01-12.645c.812-3.975 3.126-5.836 7.526-5.836l6.997-.04l-2.467 10.363c-.27 1.087-1.345 1.43-2.504 1.463c-2.074.057-2.56-.835-2.378-1.725a26 26 0 0 0 .533-2.642a.926.926 0 0 0-.75-1.067a.994.994 0 0 0-1.062.839c-.651 3.881-3.906 19.7-3.906 19.7l-10.259.057l-4.712-20.527l-6-.009Zm1.801 30.232c2.557 0 6.585-6.54 5.696-9.86c-2.95-2.95-8.594-2.737-11.332 0c-.884 3.301 3 9.86 5.636 9.86M6.9 25.888c0-5.572 6.847-5.478 6.847 0");
}

</style>
