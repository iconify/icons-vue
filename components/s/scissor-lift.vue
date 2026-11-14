<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz2e1qb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:scissor-lift" /></template>
<style>
.oz2e1qb0v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 2.75h11.5q2 0 2 2t-2 2h-4.127l-1.909 1.5l2.749 2.16q.058.046.106.102q.049.056.085.12q.036.065.059.135t.032.144q.008.073.003.147q-.006.073-.026.144t-.053.137t-.079.124t-.102.106L11.652 14l2.625 2.25H16.5q2.25 0 2.25 2.25t-2.25 2.25h-9q-2.25 0-2.25-2.25q0-1.732 1.334-2.131L9.348 14l-2.836-2.431q-.113-.097-.181-.23t-.079-.281t.035-.291q.046-.142.144-.255q.048-.056.106-.102l2.749-2.16l-1.909-1.5H6.25q-2 0-2-2t2-2m3.555 4l.695.546l.695-.546zm.695 2.454l-2.318 1.821l2.318 1.987l2.318-1.987zm1.473 7.046L10.5 14.988L9.027 16.25z");
}

</style>
