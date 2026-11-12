<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2c2_w_6w"/><path class="r59yt9kbk"/><path class="ihrvnl4wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-top-right-bold-duotone" /></template>
<style>
.ihrvnl4wp {
  fill: currentColor;
  d: path("M2.00293 10.25C1.99954 10.7944 2 11.3766 2 12C2 16.714 2.00038 19.0707 3.46484 20.5352C4.92931 21.9996 7.28596 22 12 22C12.8185 22 14.3159 21.9999 15 21.9922V9.5H2L2.00293 10.25Z");
}

.r59yt9kbk {
  fill: currentColor;
  d: path("M15 9.5V22L15.75 21.9561C18.0903 21.8589 19.5249 21.5454 20.5351 20.5352C21.9996 19.0707 22 16.714 22 12C22 11.3766 22.0004 10.7944 21.997 10.25L21.9736 9.5H15Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y2c2_w_6w {
  fill: currentColor;
  d: path("M21.9736 9.5V8.75C21.8993 6.11064 21.6154 4.5451 20.5351 3.46484C19.0707 2.00041 16.714 2 12 2C7.28597 2 4.92928 2.00038 3.46482 3.46484C2.38459 4.5451 2.1007 6.11066 2.02635 8.75L1.99998 9.5H15V22L15.75 21.9561C18.0903 21.8589 19.5249 21.5454 20.5351 20.5352C21.9996 19.0707 22 16.714 22 12C22 11.3766 22.0004 10.7944 21.997 10.25L21.9736 9.5Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
