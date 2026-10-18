<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="spgkknk4o"/><path class="kop6b_0_h"/><path class="roanorbuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-2-duotone" /></template>
<style>
.kop6b_0_h {
  fill: currentColor;
  d: path("M16 6C16 8.2091 14.2091 10 12 10C9.7909 10 8 8.2091 8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.roanorbuo {
  d: path("M12 9L12 17");
}

.spgkknk4o {
  stroke-opacity: 0.4;
  d: path("M16 15.2505C19.6443 15.7276 22 16.8071 22 18C22 19.6569 17.5228 21 12 21C6.4772 21 2 19.6569 2 18C2 16.8071 4.3557 15.7276 8 15.2505");
}

</style>
