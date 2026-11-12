<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="z-fwhccia"/><path class="kwhpv5b4r"/></g><path class="wj-op7bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-horizontal-bold-duotone" /></template>
<style>
.kwhpv5b4r {
  d: path("M11.4697 2.46979C11.7626 2.1769 12.2373 2.1769 12.5302 2.46979L18.5302 8.46979C18.8231 8.76269 18.8231 9.23746 18.5302 9.53034C18.2373 9.82321 17.7626 9.82318 17.4697 9.53034L11.9999 4.06061L6.53022 9.53034C6.23734 9.82321 5.76257 9.82318 5.46967 9.53034C5.17678 9.23745 5.17678 8.76269 5.46967 8.46979L11.4697 2.46979Z");
}

.wj-op7bjd {
  fill: currentColor;
  d: path("M22 11.25C22.4142 11.25 22.75 11.5858 22.75 12C22.75 12.4142 22.4142 12.75 22 12.75H2C1.58579 12.75 1.25 12.4142 1.25 12C1.25 11.5858 1.58579 11.25 2 11.25H22Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z-fwhccia {
  d: path("M17.4697 14.4698C17.7626 14.1769 18.2373 14.1769 18.5302 14.4698C18.8231 14.7627 18.8231 15.2375 18.5302 15.5303L12.5302 21.5303C12.2373 21.8232 11.7626 21.8232 11.4697 21.5303L5.46967 15.5303C5.17678 15.2374 5.17678 14.7627 5.46967 14.4698C5.76256 14.1769 6.23732 14.1769 6.53022 14.4698L11.9999 19.9395L17.4697 14.4698Z");
}

</style>
