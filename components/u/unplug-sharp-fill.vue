<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j5m8robuo"/><path clip-rule="evenodd" class="f_8hrabcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unplug-sharp-fill" /></template>
<style>
.f_8hrabcx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.4783 10.922L13.078 17.5217C13.4686 17.9122 13.4686 18.5454 13.078 18.9359L11.1924 20.8215C8.9794 23.0345 5.3915 23.0344 3.1785 20.8215C0.9656 18.6085 0.9655 15.0206 3.1785 12.8076L5.0641 10.922C5.4546 10.5314 6.0878 10.5314 6.4783 10.922ZM17.5217 13.078L10.922 6.4783C10.5314 6.0878 10.5314 5.4546 10.922 5.0641L12.8076 3.1785C15.0206 0.9655 18.6085 0.9656 20.8215 3.1785C23.0344 5.3915 23.0345 8.9794 20.8215 11.1924L18.9359 13.078C18.5454 13.4686 17.9122 13.4686 17.5217 13.078Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j5m8robuo {
  d: path("M7.6569 13.5147L10.3068 10.8648M10.4853 16.3431L13.1352 13.6932M3.8856 20.1144L1.7071 22.2929M20.1144 3.8856L22.2929 1.7071");
}

</style>
