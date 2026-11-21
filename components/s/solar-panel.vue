<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl0_g2bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-panel" /></template>
<style>
.bl0_g2bte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.1828 4.7007C5.6823 3.6611 6.7335 3 7.8868 3L16.1132 3C17.2665 3 18.3177 3.6611 18.8172 4.7007L21.7003 10.7007C22.6574 12.6923 21.2059 15 18.9963 15L5.0037 15C2.7941 15 1.3426 12.6923 2.2997 10.7007ZM10 3L8.0779 15M14 3L15.9221 15M3.1169 9L20.8831 9M12 15V21M8 21H16");
}

</style>
