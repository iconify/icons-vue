<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d06p-ebvs"/><path class="kaf6m4bug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-notes-two-tone" /></template>
<style>
.d06p-ebvs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 7L16 7C16.2652 7 16.5196 7.1054 16.7071 7.2929L22.7071 13.2929C22.8946 13.4804 23 13.7348 23 14L23 19C23 21.2091 21.2091 23 19 23L11 23C8.7909 23 7 21.2091 7 19L7 11C7 8.7909 8.7909 7 11 7Z");
  stroke: none;
}

.kaf6m4bug {
  d: path("M15.8284 4C15.4046 2.8015 14.2714 2 13 2H5C3.34315 2 2 3.34315 2 5V13C2 14.2714 2.8015 15.4046 4 15.8284M11 8L16 8L22 14L22 19C22 20.6569 20.6569 22 19 22L11 22C9.3431 22 8 20.6569 8 19L8 11C8 9.3431 9.3431 8 11 8ZM16 8L16 11C16 12.6569 17.3431 14 19 14L22 14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
