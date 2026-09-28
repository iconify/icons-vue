<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw5zjlb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pin-sharp" /></template>
<style>
.uw5zjlb6q {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.4407 3.0001L20.9999 9.5593L18.6248 11.9345L16.8814 10.6054L14.092 13.3948C14.713 15.3514 15.029 17.392 15.029 19.4448C15.029 19.6238 15.0266 19.8028 15.0218 19.9818L13.7433 21.0001L2.9999 10.2567L4.0182 8.9782C4.1972 8.9734 4.3762 8.971 4.5552 8.971C6.608 8.971 8.6486 9.287 10.6052 9.908L13.3946 7.1186L12.0655 5.3752L14.4407 3.0001ZM8.3716 15.6284L3.6875 20.3125");
}

</style>
