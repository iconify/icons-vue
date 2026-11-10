<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="azjucxkus"/><path class="th3wwhsdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ring-diamond-duotone" /></template>
<style>
.azjucxkus {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M12 7C16.4183 7 20 10.58 20 15C20 19.42 16.4183 23 12 23C7.5817 23 4 19.42 4 15C4 10.58 7.5817 7 12 7ZM12 9C8.6863 9 6 11.69 6 15C6 18.31 8.6863 21 12 21C15.3137 21 18 18.31 18 15C18 11.69 15.3137 9 12 9Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.th3wwhsdo {
  d: path("M13.5204 1C14.1273 1 14.7036 1.28 15.0829 1.75L16.3574 3.34C16.8365 3.94 16.8915 4.83 16.5683 5.52L15.4003 7.56C15.3502 7.65 15.2411 7.69 15.1474 7.65C14.1815 7.23 13.1186 7 12.0019 7C10.8839 7 9.8193 7.23 8.8525 7.65C8.7586 7.69 8.6497 7.65 8.5995 7.56L7.4697 5.59C7.0634 4.87 7.1335 3.98 7.6454 3.34L8.9208 1.75C9.3002 1.28 9.8752 1 10.4824 1H13.5204Z");
}

</style>
