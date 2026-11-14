<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vhk2gfxnc"/><path class="hvthmhcoi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sim-card-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvthmhcoi {
  d: path("M13.996 10.075q.174.042.34.107t.322.153t.298.194q.142.108.269.233q.126.126.235.268t.196.297q.089.155.155.32q.067.166.11.339m-1.549 6.317q-.479.197-.997.197h-2.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T9.62 18.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q8 16.004 8 15.875v-3.25q0-.313.074-.617M8 14.25h2.3M3.5 3.5l17 17");
}

.vhk2gfxnc {
  d: path("M6.873 2.901q.376-.197.789-.299T8.5 2.5h4.55q.345 0 .683.067t.656.199t.606.324q.286.191.53.435l2.45 2.45q.244.244.435.53q.192.287.324.606q.132.318.199.656T19 8.45v6.627m-1.887 6.029q-.374.194-.783.294t-.83.1h-7q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T5 18V8.938");
}

</style>
