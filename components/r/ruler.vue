<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6ckv1snn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ruler" /></template>
<style>
.j6ckv1snn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.9289 13.414L7.7574 16.243M7.7574 10.586L9.5251 12.354M10.5858 7.757L13.4142 10.586M13.4142 4.929L15.182 6.697M2.5858 18.586C1.8047 17.805 1.8047 16.538 2.5858 15.757L15.7573 2.586C16.5384 1.805 17.8047 1.805 18.5858 2.586L21.4142 5.414C22.1953 6.195 22.1953 7.462 21.4142 8.243L8.2427 21.414C7.4616 22.195 6.1953 22.195 5.4142 21.414L2.5858 18.586Z");
}

</style>
