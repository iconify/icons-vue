<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aek6-ac2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plug-zap-sharp" /></template>
<style>
.aek6-ac2d {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.7712 11.6291L12.3709 18.2288L10.4853 20.1144C8.6629 21.9369 5.7081 21.9368 3.8856 20.1144C2.0632 18.2919 2.0631 15.3371 3.8856 13.5147L5.7712 11.6291ZM7.6569 13.5147L10.3068 10.8648M10.4853 16.3431L13.1352 13.6932M3.8856 20.1144L1.7071 22.2929M20.7929 1.7071L16 6.5L22 6.5L17.2071 11.2929");
}

</style>
