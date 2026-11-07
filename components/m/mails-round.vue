<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otqh9gbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mails-round" /></template>
<style>
.otqh9gbpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 13a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm1-2l3 3c.64.64 1.72 1 3 1s2.36-.36 3-1l3-3M7 5a2 2 0 0 1 2-2h8a4 4 0 0 1 4 4v8");
}

</style>
