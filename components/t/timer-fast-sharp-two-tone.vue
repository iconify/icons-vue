<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s76_6xb8o"/><path class="j43ox5rtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-fast-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j43ox5rtj {
  d: path("M6.3699 8.2986L6.7085 8C8.1699 6.7112 10.0515 6 12 6C16.4183 6 20 9.5817 20 14C20 18.4183 16.4183 22 12 22C10.0515 22 8.1699 21.2888 6.7085 20L6.3699 19.7014M8 2L16 2M12 2L12 6M12 15L12 9M17.6569 8.3431L19.2929 6.7071M3 12L9 12M3 16L8 16");
}

.s76_6xb8o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.716 7.5571C7.3951 5.9149 9.6513 4.9969 12 5C16.9706 5 21 9.0294 21 14C21 18.9706 16.9706 23 12 23C9.6513 23.0031 7.3951 22.0851 5.716 20.4429L7.041 18.9405C5.7318 17.6298 4.9976 15.8524 5 14C4.9976 12.1476 5.7318 10.3702 7.041 9.0595L5.716 7.5571Z");
  stroke: none;
}

</style>
