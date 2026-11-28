<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="b-elmfz8t"/><path class="ncvbffzky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:replace-sharp-duotone" /></template>
<style>
.b-elmfz8t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3C8.2091 3 10 4.7909 10 7C10 9.2091 8.2091 11 6 11C3.7909 11 2 9.2091 2 7C2 4.7909 3.7909 3 6 3ZM15 13H21C21.5523 13 22 13.4477 22 14V20C22 20.5523 21.5523 21 21 21H15C14.4477 21 14 20.5523 14 20V14C14 13.4477 14.4477 13 15 13Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ncvbffzky {
  d: path("M12 7L21 7M17.7071 3.7071L21 7L17.7071 10.2929M12 17L3 17M6.2929 13.7071L3 17L6.2929 20.2929");
}

</style>
