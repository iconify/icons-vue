<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn2vdo_au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:spiral-conveyor" /></template>
<style>
.dn2vdo_au {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 7q0-2.25 7.75-2.25T19.75 7q0 1.65-7.644 2.742Q5.75 10.65 5.75 11t6.356 1.258Q19.75 13.35 19.75 15t-7.644 2.742Q5.75 18.65 5.75 19q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 19.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 19q0-1.65 7.644-2.742Q18.25 15.35 18.25 15t-6.356-1.258Q4.25 12.65 4.25 11t7.644-2.742Q18.25 7.35 18.25 7q0-.75-6.25-.75T5.75 7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T5 7.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T4.25 7");
}

</style>
