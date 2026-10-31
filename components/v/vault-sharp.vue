<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws3z5d35c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vault-sharp" /></template>
<style>
.ws3z5d35c {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L21 3L21 21L3 21ZM7 7L17 7L17 17L7 17ZM3 10L7 10M3 14L7 14M13 10L13 14");
}

</style>
