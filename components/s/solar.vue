<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbb1edm4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar" /></template>
<style>
.hbb1edm4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.4 14.8008C5.7777 14.2967 6.3708 14 7.0006 14L16.9994 14C17.6292 14 18.2223 14.2967 18.6 14.8008L21.5969 18.8008C22.5849 20.1194 21.644 22 19.9964 22L4.0036 22C2.356 22 1.4151 20.1194 2.4031 18.8008ZM10 14L8.002 22M14 14L15.998 22M3.003 18H20.997M7.9689 10C8.7286 8.4686 10.2905 7.5 12 7.5C13.7095 7.5 15.2714 8.4686 16.0311 10M12 3.5L12 2M18.0104 5.9896L19.0711 4.9289M5.9896 5.9896L4.9289 4.9289M3.9689 10H2.4689M20.0311 10H21.5311");
}

</style>
