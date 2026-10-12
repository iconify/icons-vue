<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="h6swjkqgk"/><path class="exjoxyb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unplug-sharp-two-tone" /></template>
<style>
.exjoxyb_w {
  d: path("M5.7712 11.6291L12.3709 18.2288L10.4853 20.1144C8.6629 21.9369 5.7081 21.9368 3.8856 20.1144C2.0632 18.2919 2.0631 15.3371 3.8856 13.5147L5.7712 11.6291ZM18.2288 12.3709L11.6291 5.7712L13.5147 3.8856C15.3371 2.0631 18.2919 2.0632 20.1144 3.8856C21.9368 5.7081 21.9369 8.6629 20.1144 10.4853L18.2288 12.3709ZM7.6569 13.5147L10.3068 10.8648M10.4853 16.3431L13.1352 13.6932M3.8856 20.1144L1.7071 22.2929M20.1144 3.8856L22.2929 1.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h6swjkqgk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M6.4783 10.922L13.078 17.5217C13.4686 17.9122 13.4686 18.5454 13.078 18.9359L11.1924 20.8215C8.9794 23.0345 5.3915 23.0344 3.1785 20.8215C0.9656 18.6085 0.9655 15.0206 3.1785 12.8076L5.0641 10.922C5.4546 10.5314 6.0878 10.5314 6.4783 10.922ZM17.5217 13.078L10.922 6.4783C10.5314 6.0878 10.5314 5.4546 10.922 5.0641L12.8076 3.1785C15.0206 0.9655 18.6085 0.9656 20.8215 3.1785C23.0344 5.3915 23.0345 8.9794 20.8215 11.1924L18.9359 13.078C18.5454 13.4686 17.9122 13.4686 17.5217 13.078Z");
  stroke: none;
}

</style>
