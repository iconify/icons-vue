<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx-6sxb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-aquarius-fill" /></template>
<style>
.zx-6sxb2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 10L5.6464 6.3536C5.8417 6.1583 6.1583 6.1583 6.3536 6.3536L9.6464 9.6464C9.8417 9.8417 10.1583 9.8417 10.3536 9.6464L13.6464 6.3536C13.8417 6.1583 14.1583 6.1583 14.3536 6.3536L17.6464 9.6464C17.8417 9.8417 18.1583 9.8417 18.3536 9.6464L22 6M2 18L5.6464 14.3536C5.8417 14.1583 6.1583 14.1583 6.3536 14.3536L9.6464 17.6464C9.8417 17.8417 10.1583 17.8417 10.3536 17.6464L13.6464 14.3536C13.8417 14.1583 14.1583 14.1583 14.3536 14.3536L17.6464 17.6464C17.8417 17.8417 18.1583 17.8417 18.3536 17.6464L22 14");
}

</style>
