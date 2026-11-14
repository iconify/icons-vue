<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juokdbvpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:safety-training" /></template>
<style>
.juokdbvpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.5C5.5 8 8.5 5 12 5s6.5 3 6.5 7.5m-15 0h17M12 5v2.75m0 8.75c-2-1.25-5.5-1.5-9.5-1v5c4-.5 7.5-.25 9.5 1c2-1.25 5.5-1.5 9.5-1v-5c-4-.5-7.5-.25-9.5 1Zm0 0v5");
}

</style>
