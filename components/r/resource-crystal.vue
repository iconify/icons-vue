<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qoivxwzot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:resource-crystal" /></template>
<style>
.qoivxwzot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.009 3.417l4 3.637a1.5 1.5 0 0 1 .491 1.11v8.125a1.5 1.5 0 0 1-.55 1.161l-4 3.273a1.5 1.5 0 0 1-1.9 0l-4-3.273a1.5 1.5 0 0 1-.55-1.161V8.164a1.5 1.5 0 0 1 .491-1.11l4-3.637a1.5 1.5 0 0 1 2.018 0M12 6.5v11");
}

</style>
