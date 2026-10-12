<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io4cgcigp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reinforcement-reward-sharp" /></template>
<style>
.io4cgcigp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.29 3.49l.83 2.07l.29.75l.8.05l2.22.14l.8.05l-.62.51l-1.71 1.42l-.62.51l.2.78l.55 2.15l.2.78l-.67-.43l-1.88-1.19l-.68-.43l-.68.43l-1.88 1.19l-.67.43l.2-.78l.55-2.15l.2-.78l-.62-.51l-1.71-1.42l-.62-.51l.8-.05l2.22-.14l.8-.05l.29-.75l.83-2.07l.29-.74zM4.25 14.75a8 8 0 0 0 15.5 0m-3 .5l3-.5l.75 3");
}

</style>
