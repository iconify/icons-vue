<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yrcm1ibvg"/><path class="mus5l3b9c"/><path class="y9_9cbcfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wand-sparkles-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mus5l3b9c {
  fill: currentColor;
  d: path("M6.5492 2.3739L7.4196 4.5804L9.6261 5.4508C9.8518 5.5397 10 5.7576 10 6C10 6.2424 9.8518 6.4603 9.6261 6.5492L7.4196 7.4196L6.5492 9.6261C6.4603 9.8518 6.2424 10 6 10C5.7576 10 5.5397 9.8518 5.4508 9.6261L4.5804 7.4196L2.3739 6.5492C2.1482 6.4603 2 6.2424 2 6C2 5.7576 2.1482 5.5397 2.3739 5.4508L4.5804 4.5804L5.4508 2.3739C5.5397 2.1482 5.7576 2 6 2C6.2424 2 6.4603 2.1482 6.5492 2.3739Z");
  stroke: none;
}

.y9_9cbcfr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.8433 15.2337L18.3873 16.6127L19.7663 17.1567C19.9074 17.2123 20 17.3485 20 17.5C20 17.6515 19.9074 17.7877 19.7663 17.8433L18.3873 18.3873L17.8433 19.7663C17.7877 19.9074 17.6515 20 17.5 20C17.3485 20 17.2123 19.9074 17.1567 19.7663L16.6127 18.3873L15.2337 17.8433C15.0926 17.7877 15 17.6515 15 17.5C15 17.3485 15.0926 17.2123 15.2337 17.1567L16.6127 16.6127L17.1567 15.2337C17.2123 15.0926 17.3485 15 17.5 15C17.6515 15 17.7877 15.0926 17.8433 15.2337Z");
  stroke: none;
}

.yrcm1ibvg {
  d: path("M17.4645 3L21 6.5355L6.5355 21L3 17.4645L17.4645 3ZM13.1251 7.3393L16.6607 10.8749");
}

</style>
