<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGfWQRIDOy" class="pb3_1lbls"/></defs><path class="xa621_ukv"/><path class="ru3fgc3mv"/><use href="#SVGfWQRIDOy" class="pfsdhbbki"/><use href="#SVGfWQRIDOy" class="e0ty9gbgt"/><circle class="z_6_kfacf"/><path class="ydrd-r6eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:mens-room" /></template>
<style>
.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.pb3_1lbls {
  fill: var(--svg-color--68abe6, #68abe6);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4c-1.9 2.3-2.3 5.6-2.6 8.4c-.2 2.2-2.2 14.9 3.5 11.2c.68-.45 1.23-1.07 1.6-1.8c1.2-2.1 1.9-3.5 3.3-5.6c5.3-8.6 18.8-10.5 18.8-13.5");
}

.pfsdhbbki {
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ru3fgc3mv {
  fill: var(--svg-color--2262dd, #2262dd);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

.xa621_ukv {
  fill: var(--svg-color--194fa5, #194fa5);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.ydrd-r6eh {
  fill: var(--svg-color--fff, #fff);
  d: path("M81.52 72.35c1.68-.61 2.56-2.52 1.98-4.27l-8.67-25.25c-1.13-3.49-6.4-6.13-12.74-6.13c-6.32 0-11.58 2.63-12.74 6.1l-8.56 25.29c-.59 1.75.3 3.66 1.98 4.27s3.52-.31 4.1-2.06l5.15-16.47c.09-.28.5-.22.5.08v47.79c0 2.31 1.8 4.19 4.03 4.19s4.03-1.88 4.03-4.19V71.78c0-.93.72-1.67 1.61-1.67s1.61.75 1.61 1.67v29.91c0 2.31 1.8 4.19 4.03 4.19s4.03-1.88 4.03-4.19V53.93c0-.3.4-.36.5-.08l5.07 16.45c.57 1.74 2.42 2.66 4.09 2.05");
}

.z_6_kfacf {
  cx: 62.15px;
  cy: 25.47px;
  r: 9.35px;
  fill: var(--svg-color--fff, #fff);
}

</style>
