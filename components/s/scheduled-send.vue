<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b9_xonb2a"/><circle class="rygxc4fup"/><path class="yn24rhbfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scheduled-send" /></template>
<style>
.b9_xonb2a {
  d: path("M15.82 3.61L4.18 8.14q-.93.36-.01.76l3.91 1.7Q9 11 9.4 11.92l1.7 3.91q.4.92.76-.01l4.53-11.64q.36-.93-.57-.57M9 11l3.25-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rygxc4fup {
  cx: 17.75px;
  cy: 17.75px;
  r: 3.5px;
}

.yn24rhbfo {
  d: path("M17.75 16v1.75l1.25.75");
}

</style>
