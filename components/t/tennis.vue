<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="pv98j_psr"/><path class="x0c2u-pvw"/><rect transform="rotate(-45 36.481 36.481)" class="g31tydb3n"/><path class="uuzwrxfwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tennis" /></template>
<style>
.g31tydb3n {
  width: 4.945px;
  height: 12.969px;
  x: 34.009px;
  y: 29.997px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.759px;
  ry: 0.759px;
}

.pv98j_psr {
  cx: 12.233px;
  cy: 35.06px;
  r: 4.338px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uuzwrxfwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.016 29.77c4.082.419 9.859 1.528 11.668 3.337m-.914-14.091c.419 4.082 1.528 9.859 3.337 11.668M29.72 18.665L18.666 29.72m-3.954-1.123l13.886-13.885M11.43 26.803L26.805 11.43M8.66 24.484L24.483 8.66M6.58 21.487L21.488 6.581M5.53 17.462L17.463 5.53M5.545 15.726l14.097 14.097M6.647 11.751l17.538 17.54m3.155-1.937L8.768 8.784m2.954-2.123l17.554 17.554M15.682 5.545L29.83 19.693");
}

.x0c2u-pvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.629 39.38c.114-1.24-.304-2.516-1.252-3.464s-2.224-1.365-3.463-1.251m8.639.79c-1.239.114-2.516-.304-3.464-1.251s-1.365-2.225-1.25-3.463M24.603 8.778c-4.37-4.37-11.455-4.37-15.825 0s-4.37 11.455 0 15.825c5.562 5.563 14.198 7.114 18.568 2.743c4.37-4.37 2.82-13.006-2.743-18.568");
}

</style>
