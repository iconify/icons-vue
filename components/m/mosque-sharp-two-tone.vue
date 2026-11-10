<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ep7utxbnq"/><path class="ymn7_bc0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mosque-sharp-two-tone" /></template>
<style>
.ep7utxbnq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 10C14 11.07 13.715 12.1 13.195 13H16V7C16 6.88 16.02 6.77 16.059 6.66L17.618 2.32C17.904 1.53 18.656 1 19.5 1C20.344 1 21.096 1.53 21.382 2.32L22.941 6.66C22.98 6.77 23 6.88 23 7V22C23 22.55 22.552 23 22 23H2C1.448 23 1 22.55 1 22V14C1 13.45 1.448 13 2 13H2.805C2.285 12.1 2 11.07 2 10C2 8.11 2.889 6.33 4.399 5.2L6.867 3.35C7.186 3.15 7.621 3 8 3C8.433 3 8.854 3.14 9.2 3.4L11.6 5.2C13.11 6.33 14 8.11 14 10Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ymn7_bc0o {
  d: path("M17 22V7L18.559 2.66C18.702 2.26 19.078 2 19.5 2C19.922 2 20.298 2.26 20.441 2.66L22 7V22H17ZM17 22H2V14H17M5 14C3.741 13.06 3 11.57 3 10C3 8.43 3.741 6.94 5 6L7.4 4.2C7.573 4.07 7.784 4 8 4C8.216 4 8.427 4.07 8.6 4.2L11 6C12.259 6.94 13 8.43 13 10C13 11.57 12.259 13.06 11 14M6 22V19C6 17.9 6.895 17 8 17C9.105 17 10 17.9 10 19V22");
}

</style>
