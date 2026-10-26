<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="detmhnb4z"/><path class="oeg3o4bzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-off-sharp-two-tone" /></template>
<style>
.detmhnb4z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M23 17.3432L23 18C23.0001 18.3514 22.8158 18.677 22.5145 18.8577L6.6569 3L11 3C11.008 3 11.0159 3 11.0239 3.0001L14 3.0001C14.5523 3.0001 15 3.4478 15 4.0001L15 7L17 7C17.0039 7 17.0079 7 17.0118 7.0001L17.8284 7.0001C18.0936 7.0001 18.348 7.1054 18.5355 7.293L22.7071 11.4646C22.8947 11.6521 23 11.9065 23 12.1717L23 17.3432ZM18.9999 18.9999L14.1716 19C14.0581 18.6788 14 18.3407 14 18L14 19L2 19C1.4477 19 1 18.5523 1 18L1 4C0.9999 3.4477 1.4477 2.9999 2 2.9999L2.9999 2.9999L18.9999 18.9999Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oeg3o4bzk {
  d: path("M14 18L14 14M4 4L2 4L2 18L5 18M9 18L14 18M9 18C9 19.1046 8.1046 20 7 20C5.8954 20 5 19.1046 5 18C5 16.8954 5.8954 16 7 16C8.1046 16 9 16.8954 9 18ZM18.8233 18.8233C18.5094 19.5172 17.8111 20 17 20C15.8954 20 15 19.1046 15 18C15 17.1889 15.4828 16.4906 16.1767 16.1767M1.7071 1.7071L22.2929 22.2929");
}

</style>
