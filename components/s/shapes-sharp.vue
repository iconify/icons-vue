<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byzoqfnso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shapes-sharp" /></template>
<style>
.byzoqfnso {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.7071 2.7071L10.2929 10.2929M10.2929 2.7071L2.7071 10.2929M17.5 3L21 10L14 10L17.5 3ZM10 17.5C10 19.433 8.433 21 6.5 21C4.567 21 3 19.433 3 17.5C3 15.567 4.567 14 6.5 14C8.433 14 10 15.567 10 17.5ZM14 14L21 14L21 21L14 21L14 14Z");
}

</style>
