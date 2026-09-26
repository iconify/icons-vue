<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emc5ew3im"/><path class="opx_29e6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-off-two-tone" /></template>
<style>
.emc5ew3im {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.82843 20.82843C20.07828 21.57857 19.06087 22 18 22H6C3.79086 22 2 20.20914 2 18V6C2 4.93913 2.42143 3.92172 3.17157 3.17157ZM7.94975 3.70711C7.76221 3.51957 7.65685 3.26522 7.65685 3C7.65685 2.44772 8.10457 2 8.65685 2H18C20.20914 2 22 3.79086 22 6V15.34315C22 15.89543 21.55228 16.34315 21 16.34315C20.73478 16.34315 20.48043 16.23779 20.29289 16.05025Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.opx_29e6j {
  d: path("M20.12132 20.12132C19.55871 20.68393 18.79565 21 18 21H6C4.34315 21 3 19.65685 3 18V6C3 5.20435 3.31607 4.44129 3.87868 3.87868M3 9H9M3 15H15M12 12V21M2 2L22 22");
}

</style>
