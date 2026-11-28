<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqgczk5nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-code-sharp" /></template>
<style>
.mqgczk5nd {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 17L7 17L3 21L3 3ZM10.2929 7.2071L10 7.5L7.5 10L10 12.5L10.2929 12.7929M13.7071 7.2071L14 7.5L16.5 10L14 12.5L13.7071 12.7929");
}

</style>
