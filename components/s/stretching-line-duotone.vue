<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xvkwtxc3k"/><path class="pfa6pubss"/><path class="w5098j-mw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stretching-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pfa6pubss {
  stroke-linejoin: round;
  d: path("M5 22L8.84856 20.6272C9.30437 20.4646 9.68576 20.1423 9.92204 19.7199L12.6343 14.8717C12.8012 14.5733 12.8889 14.2371 12.8889 13.8953V11.2748C12.8889 10.1979 11.7878 9.47189 10.798 9.89609L8.34221 10.9486C7.35935 11.3698 7.12031 12.6548 7.88594 13.4013L8.5 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w5098j-mw {
  stroke-linejoin: round;
  d: path("M18.9993 22.0002V16.7681C18.9993 15.5355 17.8952 14.5962 16.6786 14.7939L15.666 14.9585");
}

.xvkwtxc3k {
  cx: 14.5px;
  cy: 4.5px;
  r: 2.5px;
}

</style>
