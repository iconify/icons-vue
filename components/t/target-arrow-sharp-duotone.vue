<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="by8revb0d"/><path class="q9mmsusff"/><path class="tmuf4sbck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:target-arrow-sharp-duotone" /></template>
<style>
.by8revb0d {
  stroke-opacity: 0.4;
  d: path("M21.2933 8.2359L21.5168 8.9289C21.8369 9.9212 22 10.9574 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C13.0426 2 14.0788 2.1631 15.0711 2.4832L15.7641 2.7067");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q9mmsusff {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.0503 7.0503C5.7846 8.3159 5 10.0673 5 12C5 15.866 8.134 19 12 19C15.866 19 19 15.866 19 12C19 10.0673 18.2154 8.3159 16.9497 7.0503C15.6841 5.7846 13.9327 5 12 5C10.0673 5 8.3159 5.7846 7.0503 7.0503Z");
  stroke: none;
}

.tmuf4sbck {
  d: path("M19.0711 4.9289L19.0711 2L19.0711 1M19.0711 4.9289L22 4.9289L23 4.9289M11.7071 12.2929L12 12L16.2426 7.7574L19.0711 4.9289");
}

</style>
