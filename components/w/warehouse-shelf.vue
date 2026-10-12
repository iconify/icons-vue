<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="juowy3rnn"/><rect class="smu78acyt"/><path class="v0vibhafi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warehouse-shelf" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.juowy3rnn {
  d: path("M3.5 2.75v18.5m17-18.5v18.5M3.5 5.5h17M3.5 13h17m-17 7.5h17");
}

.smu78acyt {
  width: 7.5px;
  height: 4.5px;
  x: 8px;
  y: 8.5px;
  rx: 0.75px;
}

.v0vibhafi {
  d: path("M11.75 8.5v2");
}

</style>
