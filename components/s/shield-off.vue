<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb4gmys6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off" /></template>
<style>
.nb4gmys6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h8a2 2 0 0 1 2 2v5c0 .958-.106 1.855-.305 2.695m-1.952 4.048C16.3 18.59 14.279 19.987 12 21c-4.5-2-8-5.5-8-11V5c0-.552.224-1.052.586-1.414M3 2l19 19");
}

</style>
