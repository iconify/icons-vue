<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_mg51byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:syringe" /></template>
<style>
.z_mg51byp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.9289 5.8284L5.8579 13.8995C5.4828 14.2746 5.2721 14.7833 5.2721 15.3137C5.2721 15.8441 5.4828 16.3529 5.8579 16.7279L7.2721 18.1421C7.6471 18.5172 8.1559 18.7279 8.6863 18.7279C9.2167 18.7279 9.7254 18.5172 10.1005 18.1421L18.1716 10.0711M6.565 17.435L3 21M12.5147 4.4142L16.0502 7.9498L18.8787 5.1213M16.7574 3L21 7.2426M16.0502 7.9498L19.5858 11.4853M7.7574 12L9.1716 13.4142M10.5858 9.1716L12 10.5858");
}

</style>
