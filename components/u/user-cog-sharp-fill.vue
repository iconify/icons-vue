<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sg2zllfnh"/><path class="q582ufb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-cog-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q582ufb0z {
  d: path("M20.6667 17C20.6667 18.4728 19.4728 19.6667 18 19.6667C16.5272 19.6667 15.3333 18.4728 15.3333 17C15.3333 15.5272 16.5272 14.3333 18 14.3333C19.4728 14.3333 20.6667 15.5272 20.6667 17ZM20.99 17L23 17M20.1142 19.1142L21.5355 20.5355M18 19.99L18 22M15.8858 19.1142L14.4645 20.5355M15.01 17L13 17M15.8858 14.8858L14.4645 13.4645M18 14.01L18 12M20.1142 14.8858L21.5355 13.4645");
}

.sg2zllfnh {
  fill: currentColor;
  d: path("M10 13C10.3396 13 10.6733 13.0255 11 13.0723V22H2C1.44772 22 1 21.5523 1 21V20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

</style>
