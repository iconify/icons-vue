<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tklfdyblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-arrow-up-right-sharp" /></template>
<style>
.tklfdyblv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 17L7 17L3 21L3 3ZM8 7L9 7L15 7L15 13L15 14M8.7071 13.2929L9 13L14.5 7.5L14.8536 7.1464");
}

</style>
