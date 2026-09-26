<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9qq4ypa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-off-sharp" /></template>
<style>
.lh9qq4ypa {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 17L7 17L3 21L3 3M7.6569 3L21 3L21 16.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
