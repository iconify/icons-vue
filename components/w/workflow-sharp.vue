<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrg4yrmcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:workflow-sharp" /></template>
<style>
.qrg4yrmcl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4L11 4L11 10L3 10L3 4ZM13 14L21 14L21 20L13 20L13 14ZM7 10L7 17L13 17");
}

</style>
