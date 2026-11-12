<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hao-y3_km"/><path class="csp4cxb4v"/><path class="ptrg_gs-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-left-bold-duotone" /></template>
<style>
.csp4cxb4v {
  fill: currentColor;
  d: path("M9.00002 9.5V22L8.25002 21.9561C5.90966 21.8589 4.47508 21.5454 3.46486 20.5352C2.00041 19.0707 2.00002 16.714 2.00002 12C2.00002 11.3766 1.99956 10.7944 2.00295 10.25L2.02639 9.5H9.00002Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hao-y3_km {
  fill: currentColor;
  d: path("M2.02639 9.5V8.75C2.10074 6.11064 2.38461 4.5451 3.46486 3.46484C4.92933 2.00041 7.28601 2 12 2C16.714 2 19.0707 2.00038 20.5352 3.46484C21.6154 4.5451 21.8993 6.11066 21.9737 8.75L22 9.5H9.00002V22L8.25002 21.9561C5.90966 21.8589 4.47508 21.5454 3.46486 20.5352C2.00041 19.0707 2.00002 16.714 2.00002 12C2.00002 11.3766 1.99956 10.7944 2.00295 10.25L2.02639 9.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ptrg_gs-t {
  fill: currentColor;
  d: path("M21.9971 10.25C22.0005 10.7944 22 11.3766 22 12C22 16.714 21.9996 19.0707 20.5352 20.5352C19.0707 21.9996 16.714 22 12 22C11.1815 22 9.68405 21.9999 9 21.9922V9.5H22L21.9971 10.25Z");
}

</style>
