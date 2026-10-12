<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y79ihqb7f"/><path clip-rule="evenodd" class="sxz4g25lf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unplug-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxz4g25lf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.8925 12.3362L11.6638 16.1075C12.8354 17.279 12.8354 19.1785 11.6638 20.3501L11.1924 20.8215C8.9794 23.0345 5.3915 23.0344 3.1785 20.8215C0.9656 18.6085 0.9655 15.0206 3.1785 12.8076L3.6499 12.3362C4.8215 11.1646 6.721 11.1646 7.8925 12.3362ZM16.1075 11.6638L12.3362 7.8925C11.1646 6.721 11.1646 4.8215 12.3362 3.6499L12.8076 3.1785C15.0206 0.9655 18.6085 0.9656 20.8215 3.1785C23.0344 5.3915 23.0345 8.9794 20.8215 11.1924L20.3501 11.6638C19.1785 12.8354 17.279 12.8354 16.1075 11.6638Z");
  stroke: none;
}

.y79ihqb7f {
  stroke-opacity: 0.4;
  d: path("M7.6569 13.5147L10.0139 11.1577M10.4853 16.3431L12.8423 13.9861M3.8856 20.1144L2 22M20.1144 3.8856L22 2");
}

</style>
