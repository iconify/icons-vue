<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uspitw7xi"/><path class="d6alq3bav"/><path class="dxon-mtqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-left-line-duotone" /></template>
<style>
.d6alq3bav {
  d: path("M11 3H11.9091M11 21H11.9091M14.0909 3H15C15.4354 3 15.8373 3 16.2089 3.00321M19.0874 3.27719C19.5057 3.40719 19.8408 3.59815 20.1213 3.87868C20.4018 4.15921 20.5928 4.49432 20.7228 4.91261M20.9968 7.79109C21 8.16269 21 8.56459 21 9V10.3636M21 13.6364V15C21 15.4354 21 15.8373 20.9968 16.2089M20.7228 19.0874C20.5928 19.5057 20.4018 19.8408 20.1213 20.1213C19.8408 20.4018 19.5057 20.5928 19.0874 20.7228M16.2089 20.9968C15.8373 21 15.4354 21 15 21H14.0909");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.dxon-mtqm {
  d: path("M12 2V22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uspitw7xi {
  d: path("M12 3H11C7.22876 3 5.34315 3 4.17157 4.17157C3 5.34315 3 7.22876 3 11V13C3 16.7712 3 18.6569 4.17157 19.8284C5.34315 21 7.22876 21 11 21H12");
}

</style>
