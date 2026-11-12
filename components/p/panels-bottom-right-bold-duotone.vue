<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiq_gybtr"/><path class="qgwq-wbxv"/><path class="f7ztvmbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-right-bold-duotone" /></template>
<style>
.eiq_gybtr {
  fill: currentColor;
  d: path("M21.9736 14.5L21.9736 15.25C21.8993 17.8894 21.6154 19.4549 20.5351 20.5352C19.0707 21.9996 16.714 22 12 22C7.28597 22 4.92928 21.9996 3.46482 20.5352C2.38459 19.4549 2.1007 17.8893 2.02635 15.25L1.99998 14.5L15 14.5L15 2L15.75 2.04394C18.0903 2.14114 19.5249 2.45463 20.5351 3.46484C21.9996 4.92931 22 7.28597 22 12C22 12.6234 22.0004 13.2056 21.9971 13.75L21.9736 14.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.f7ztvmbgu {
  fill: currentColor;
  d: path("M2.00293 13.75C1.99954 13.2056 2 12.6234 2 12C2 7.28595 2.00038 4.92931 3.46484 3.46484C4.92931 2.00038 7.28596 2 12 2C12.8185 2 14.316 2.00015 15 2.00781L15 14.5L2 14.5L2.00293 13.75Z");
}

.qgwq-wbxv {
  fill: currentColor;
  d: path("M15 14.5L15 2L15.75 2.04394C18.0903 2.14114 19.5249 2.45463 20.5351 3.46484C21.9996 4.92931 22 7.28597 22 12C22 12.6234 22.0004 13.2056 21.997 13.75L21.9736 14.5L15 14.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
