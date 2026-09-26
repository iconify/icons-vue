<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn62k951t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shuffle-sharp" /></template>
<style>
.kn62k951t {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6L8.308 6L10.5316 9.6139M13.4684 14.3861L15.692 18L21 18M2 18L8.308 18L15.692 6L21 6M17.7071 2.7071L21 6L17.7071 9.2929M17.7071 14.7071L21 18L17.7071 21.2929");
}

</style>
