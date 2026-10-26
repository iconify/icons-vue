<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjhx4ubyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rocket-vertical-off-sharp" /></template>
<style>
.cjhx4ubyg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.2191 8.2191C7.9921 9.1479 7.8743 10.1087 7.8743 11.0828C7.8743 11.7657 7.9323 12.4475 8.0477 13.1206L5 16.1684L8.1708 22L9.3652 20.8056L14.6348 20.8056L15.8292 22L18.0027 18.0027M14.6348 20.8056L15.5379 15.5379M9.3652 20.8056L8.0477 13.1206M16.1186 11.4966C16.1233 11.3588 16.1257 11.2208 16.1257 11.0828C16.1257 7.6016 14.6216 4.2903 12 1.9999C10.918 2.9452 10.0264 4.0644 9.3523 5.2976M1.7071 1.7071L22.2929 22.2929");
}

</style>
