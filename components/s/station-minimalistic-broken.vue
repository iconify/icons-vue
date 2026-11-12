<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="aahgoh0mn"/><path class="or7sfdc_t"/><path class="wruzqvbcf"/><path class="w8fcmcc3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-minimalistic-broken" /></template>
<style>
.aahgoh0mn {
  d: path("M13.25 8.75C13.25 9.44036 12.6904 10 12 10C11.3096 10 10.75 9.44036 10.75 8.75C10.75 8.05964 11.3096 7.5 12 7.5C12.6904 7.5 13.25 8.05964 13.25 8.75Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.or7sfdc_t {
  d: path("M12 4.82189C9.6804 4.82189 7.8 6.717 7.8 9.05473C7.8 10.2017 8.25268 11.2422 8.9878 12.0045M12 2C15.866 2 19 5.15851 19 9.05473C19 10.9647 18.2468 12.6975 17.0235 13.9677M7.00778 14C5.76601 12.7269 5 10.981 5 9.05473C5 7.12849 5.76601 5.38255 7.00778 4.10946M15.0432 11.972C15.76 11.2127 16.2 10.1855 16.2 9.05473C16.2 8.30908 16.0087 7.60845 15.6728 7");
}

.w8fcmcc3c {
  d: path("M14.5 17.5H9.5");
}

.wruzqvbcf {
  stroke-linejoin: round;
  d: path("M16 22L12 10L8 22");
}

</style>
