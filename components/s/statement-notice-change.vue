<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dc2iwvnvl"/><path class="flc_k6b4r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:statement-notice-change" /></template>
<style>
.dc2iwvnvl {
  d: path("M16.569 4.047q.152.025.301.063q.15.038.295.09q.145.051.285.115q.141.063.275.139t.26.164t.246.185t.228.207q.11.108.21.225t.188.244q.089.125.167.258q.077.133.143.273q.065.139.119.284t.093.293t.067.3t.04.306q.014.153.014.307v5.642M13.415 21.5H8q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T4.5 18V7.5q0-.156.014-.312q.014-.155.042-.309q.027-.154.069-.304q.041-.151.095-.297q.055-.147.122-.287q.068-.141.147-.276q.08-.134.171-.261q.091-.126.194-.245q.102-.118.214-.226t.234-.207q.122-.098.251-.185q.13-.087.267-.161t.28-.138q.143-.062.291-.112q.149-.049.301-.085t.306-.059M8 9h8m-8 3.5h5.6M8 16h3m-.75-12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m9.871 11.879a3 3 0 1 1-4.242 0");
}

.flc_k6b4r {
  d: path("m15.5 14.5l.25 1.5l1.5.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
