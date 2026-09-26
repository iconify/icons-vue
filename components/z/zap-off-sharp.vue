<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcvru_b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zap-off-sharp" /></template>
<style>
.tcvru_b9i {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.6213 13.3786L20.9999 10L14.2426 10M13.1553 8.9127L14 3.0001L10.6214 6.3787M8.5 8.5L3.0001 14L11 14L10 20.9999L15.5 15.5M1.7071 1.7071L22.2929 22.2929");
}

</style>
