<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_nct9uns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-off-sharp" /></template>
<style>
.a_nct9uns {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.4697 17.4697C16.5283 19.5515 14.4333 21 12 21C8.6863 21 6 18.3137 6 15L6 9C6 8.1196 6.1896 7.2835 6.5303 6.5303M8.4056 4.0922L9.2982 3.6413C10.1102 3.2311 11.0281 3 12 3C15.3137 3 18 5.6863 18 9L18 13.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
