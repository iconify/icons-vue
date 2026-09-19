<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="jad34ebki"/><g class="y9tr6bcfx"><rect class="fs_1fac5z"/><path class="q_f5njbmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:medplus" /></template>
<style>
.fs_1fac5z {
  width: 11px;
  height: 11px;
  x: 18.5px;
  y: 13.561px;
  rx: 1.189px;
  ry: 1.189px;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.jad34ebki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 32.725v-4.926l2.639 4.931l2.639-4.924v4.924m10.025 0V27.8h1.41c.977 0 1.769.741 1.769 1.656s-.792 1.656-1.77 1.656h-1.41m4.87-3.313v4.315c0 .34.295.616.66.616h.197m1.413-3.267v2.034c0 .681.59 1.233 1.32 1.233h0c.728 0 1.32-.552 1.32-1.233v-2.034m1.665 2.992c.24.189.5.275 1.085.275h.296c.482 0 .872-.365.872-.816h0c0-.452-.39-.817-.872-.817h-.592c-.482 0-.872-.366-.872-.817h0c0-.451.39-.817.872-.817h.296c.584 0 .844.087 1.085.276m-19.855 2.675a1.37 1.37 0 0 1-.882.316h0c-.73 0-1.32-.552-1.32-1.233v-.801c0-.681.59-1.233 1.32-1.233h0c.728 0 1.32.552 1.32 1.233v.4h-2.64m6.86-.4c0-.681-.59-1.233-1.32-1.233h0c-.728 0-1.319.552-1.319 1.233v.801c0 .681.591 1.233 1.32 1.233h0c.729 0 1.32-.552 1.32-1.233m-.001 1.233v-4.931");
}

.q_f5njbmf {
  d: path("M20.634 19.061h6.732M24 15.695v6.732");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
