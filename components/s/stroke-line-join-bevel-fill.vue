<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iffz8bcuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stroke-line-join-bevel-fill" /></template>
<style>
.iffz8bcuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21V11.4142C3 11.149 3.1054 10.8946 3.2929 10.7071L10.7071 3.2929C10.8946 3.1054 11.149 3 11.4142 3H21M11 21V12C11 11.4477 11.4477 11 12 11H21");
}

</style>
