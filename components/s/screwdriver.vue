<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-p28gbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:screwdriver" /></template>
<style>
.u-p28gbuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.4394 11.5607L13.5 12.6213C14.0858 13.2071 14.0858 14.1569 13.5 14.7426L7.1214 21.1213C5.9498 22.2929 4.0503 22.2929 2.8787 21.1213C1.7071 19.9497 1.7071 18.0503 2.8787 16.8787L9.2574 10.5C9.8431 9.9142 10.7929 9.9142 11.3787 10.5L12.4394 11.5607ZM12.4394 11.5607L17 7M17 7L17 4L21 2L22 3L20 7H17Z");
}

</style>
