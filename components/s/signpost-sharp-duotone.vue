<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lxisacj0a"/><path clip-rule="evenodd" class="f0meycbhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:signpost-sharp-duotone" /></template>
<style>
.f0meycbhz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.412 3H18.824C19.048 3 19.266 3.075 19.442 3.214L22.618 5.714C22.859 5.904 22.999 6.194 22.999 6.5C22.999 6.806 22.859 7.096 22.618 7.286L19.442 9.786C19.266 9.924 19.048 10 18.824 10H6C5.448 10 5 9.552 5 9V4C5 3.448 5.448 3 6 3H12.412ZM11.588 19H5.176C4.952 19 4.734 18.924 4.558 18.786L1.382 16.286C1.141 16.096 1.001 15.807 1.001 15.5C1.001 15.193 1.141 14.904 1.382 14.714L4.558 12.214C4.734 12.076 4.952 12 5.176 12H18C18.552 12 19 12.448 19 13V18C19 18.552 18.552 19 18 19H11.588Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lxisacj0a {
  stroke-opacity: 0.4;
  d: path("M12 1V4M12 9V13M12 18V22M7 22H17");
}

</style>
