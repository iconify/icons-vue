<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni_sulbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mandatory-hard-hat" /></template>
<style>
.ni_sulbbq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.272 13.331q.218-3.195 2.541-5.518Q8.376 5.25 12 5.25t6.187 2.563q2.323 2.323 2.541 5.518q.502.144.9.541q.622.623.622 1.503t-.622 1.503q-.623.622-1.503.622H3.875q-.88 0-1.503-.622q-.622-.623-.622-1.503t.622-1.503q.398-.397.9-.541m7.978-6.547q-2.523.236-4.377 2.089q-1.853 1.854-2.089 4.377h14.432q-.236-2.523-2.089-4.377q-1.854-1.853-4.377-2.089V10q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T11.25 10z");
}

</style>
