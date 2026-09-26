<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s446_nmsp"/><path class="bmsmuq-rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-two-tone" /></template>
<style>
.bmsmuq-rv {
  d: path("M12 6C16.4183 6 20 9.5817 20 14C20 18.4183 16.4183 22 12 22C7.5817 22 4 18.4183 4 14C4 9.5817 7.5817 6 12 6ZM9 2L15 2M12 2L12 6M12 14L12 10M17.6569 8.3431L19 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s446_nmsp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5C16.9706 5 21 9.0294 21 14C21 18.9706 16.9706 23 12 23C7.0294 23 3 18.9706 3 14C3 9.0294 7.0294 5 12 5Z");
  stroke: none;
}

</style>
