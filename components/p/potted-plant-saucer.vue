<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0ay22bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:potted-plant-saucer" /></template>
<style>
.t0ay22bld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.765 13h8.47a1.75 1.75 0 0 1 1.693 2.192l-.587 2.25a1.75 1.75 0 0 1-1.693 1.308H8.352a1.75 1.75 0 0 1-1.693-1.308l-.587-2.25A1.75 1.75 0 0 1 7.765 13M4 18.75h16l-1.5 2.75h-13ZM12 13V8m0 1.5c-4.5 0-7-2.5-7-7c4.5 0 7 2.5 7 7M12 8c4 0 7-2.25 7-5.5c-4 0-7 2-7 5.5");
}

</style>
