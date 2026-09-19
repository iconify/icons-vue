<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_1p7wgej"/><circle class="wao2lt9dx"/><path class="a6c5e2b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:network-tools-library" /></template>
<style>
.a6c5e2b5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.754 23.404h-2.747a5.2 5.2 0 0 1-1.783 2.68c-.887.71-2.005 1.12-3.224 1.12s-2.337-.41-3.223-1.12m-4.531-5.494h2.747a5.13 5.13 0 0 1 1.783-2.67c.887-.708 2.005-1.13 3.224-1.13s2.337.422 3.224 1.13");
}

.d_1p7wgej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.523 31.216H10.477V13.895c0-.615.499-1.113 1.114-1.113h24.818c.615 0 1.114.498 1.114 1.113zm0 0l5.977 4.002h-39l5.977-4.002");
}

.wao2lt9dx {
  cx: 24px;
  cy: 21.999px;
  r: 1.902px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
