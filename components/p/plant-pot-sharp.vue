<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1nlwobem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plant-pot-sharp" /></template>
<style>
.d1nlwobem {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.6603 2.0014L18.5583 2.8602C18.0327 5.7587 15.5089 7.8661 12.5632 7.8661C12.3751 7.8661 12.1872 7.8574 12 7.84C12.1282 4.6823 14.6494 2.1469 17.8063 2.0008ZM5.349 3.1154C5.5362 3.098 5.7241 3.0893 5.9121 3.0893C9.181 3.0893 11.8674 5.6688 12 8.935C11.8128 8.9524 11.6249 8.9611 11.4368 8.9611C8.168 8.9611 5.4816 6.3815 5.349 3.1154ZM4 14L5 14L19 14L20 14M6.5 14L8 22L16 22L17.5 14M12 7.84L12 8.935L12 14");
}

</style>
