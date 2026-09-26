<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddo040ffb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:siren-sharp" /></template>
<style>
.ddo040ffb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 17L7 13C7 10.2386 9.2386 8 12 8C14.7614 8 17 10.2386 17 13L17 17M4 17L20 17L20 21L4 21L4 17ZM5.9289 6.9289L4.636 5.636M12 5L12 2M18.0711 6.9289L19.364 5.636");
}

</style>
