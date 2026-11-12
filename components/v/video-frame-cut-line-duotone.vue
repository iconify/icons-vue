<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dwa9fqbkg"/><path class="fenutzb3t"/><path class="mtd-u7d6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-line-duotone" /></template>
<style>
.dwa9fqbkg {
  stroke-linejoin: round;
  d: path("M14.5 3.00342C17.2939 3.0238 18.8237 3.1669 19.8284 4.17161C21 5.34318 21 7.2288 21 11V13C21 16.7713 21 18.6569 19.8284 19.8285C18.8237 20.8332 17.2939 20.9763 14.5 20.9966M9.49991 20.9966C6.70609 20.9763 5.17627 20.8332 4.17157 19.8285C3 18.6569 3 16.7713 3 13V11C3 7.2288 3 5.34318 4.17157 4.17161C5.17627 3.16691 6.70609 3.0238 9.49991 3.00342");
}

.fenutzb3t {
  d: path("M12 2V3.66667M12 22V20.3333M12 7V10.3333M12 13.6667V17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mtd-u7d6k {
  d: path("M17 4V8.5M17 8.5V15.5M17 8.5H20.5M17 15.5V20M17 15.5H20.5M7 4V8.5M7 8.5V15.5M7 8.5H3.5M7 15.5V20M7 15.5H3.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
