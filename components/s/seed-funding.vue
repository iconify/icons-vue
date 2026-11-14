<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcosl0b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:seed-funding" /></template>
<style>
.fcosl0b0k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25q-6.039 0-7.372 4.099q-.118.067-.205.172t-.131.233Q9.612 5.25 6 5.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 6q0 4.95 6 5.233v1.53q-2.774.096-4.832.919Q3.75 14.75 3.75 16.5v2q0 1.75 2.668 2.818q2.331.932 5.582.932t5.582-.932Q20.25 20.25 20.25 18.5v-2q0-1.75-2.668-2.818q-2.058-.823-4.832-.919v-3.03q7-.318 7-6.733q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 2.25M5.313 18.779q.479.288 1.105.539q2.331.932 5.582.932t5.582-.932q.626-.251 1.105-.539q-.267.588-1.662 1.146q-2.063.825-5.025.825t-5.025-.825q-1.395-.558-1.662-1.146");
}

</style>
