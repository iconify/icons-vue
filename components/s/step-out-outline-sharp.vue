<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l--2hsb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:step-out-outline-sharp" /></template>
<style>
.l--2hsb_e {
  fill: currentColor;
  d: path("M10.23 20.772q-.73-.729-.73-1.77t.729-1.771t1.769-.731t1.771.729t.731 1.769t-.728 1.771t-1.77.731t-1.771-.728M11.5 14V5.133L8.4 8.189L7.711 7.5L12 3.212L16.288 7.5l-.713.689L12.5 5.114V14z");
}

</style>
