<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_aablbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:maximize-2-sharp" /></template>
<style>
.v_aablbdu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10L3 3L10 3M9.2929 9.2929L3.1757 3.1757M21 10L21 3L14 3M14.7071 9.2929L20.8243 3.1757M21 14L21 21L14 21M14.7071 14.7071L20.8243 20.8243M3 14L3 21L10 21M9.2929 14.7071L3.1757 20.8243");
}

</style>
