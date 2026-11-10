<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k26bmlfcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mosque-sharp" /></template>
<style>
.k26bmlfcm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 22V7L18.559 2.66C18.702 2.26 19.078 2 19.5 2C19.922 2 20.298 2.26 20.441 2.66L22 7V22H17ZM17 22H2V14H17M5 14C3.741 13.06 3 11.57 3 10C3 8.43 3.741 6.94 5 6L7.4 4.2C7.573 4.07 7.784 4 8 4C8.216 4 8.427 4.07 8.6 4.2L11 6C12.259 6.94 13 8.43 13 10C13 11.57 12.259 13.06 11 14M6 22V19C6 17.9 6.895 17 8 17C9.105 17 10 17.9 10 19V22");
}

</style>
