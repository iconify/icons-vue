<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="gt5hhdb4l"/><path class="xf15-zgaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket-vertical-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.gt5hhdb4l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.1239 17.9524L14.6348 20.8056L9.3652 20.8056L8.0477 13.1206C7.9323 12.4474 7.8743 11.7656 7.8743 11.0826C7.8743 10.1178 7.9901 9.1564 8.2191 8.2191L15.5379 15.538L15.1239 17.9524ZM9.2143 5.5575C9.9104 4.2067 10.8555 2.9996 12 1.9999C14.6216 4.2902 16.1257 7.6016 16.1257 11.0828C16.1257 11.5218 16.1017 11.9606 16.0539 12.397L9.2143 5.5575Z");
  stroke: none;
}

.xf15-zgaq {
  d: path("M8.2191 8.2191C7.9921 9.1479 7.8743 10.1087 7.8743 11.0828C7.8743 11.7657 7.9323 12.4475 8.0477 13.1206L5 16.1684L8.1708 22L9.3652 20.8056L14.6348 20.8056L15.8292 22L18.0027 18.0027M14.6348 20.8056L15.5379 15.5379M9.3652 20.8056L8.0477 13.1206M16.1186 11.4966C16.1233 11.3588 16.1257 11.2208 16.1257 11.0828C16.1257 7.6016 14.6216 4.2903 12 1.9999C10.918 2.9452 10.0264 4.0644 9.3523 5.2976M1.7071 1.7071L22.2929 22.2929");
}

</style>
