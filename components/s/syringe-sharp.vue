<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m40s62-9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:syringe-sharp" /></template>
<style>
.m40s62-9h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.9289 5.8284L4.4436 15.3137L8.6863 19.5564L18.1716 10.0711M6.565 17.435L2.7071 21.2929M12.2218 4.1213L16.0502 7.9498L18.8787 5.1213M16.4645 2.7071L21.2929 7.5355M16.0502 7.9498L19.8787 11.7782M7.7574 12L9.4645 13.7071M10.5858 9.1716L12.2929 10.8787");
}

</style>
