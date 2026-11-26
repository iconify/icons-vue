<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xstwkde2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:zodiac-aries-fill" /></template>
<style>
.xstwkde2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6C3 4.3431 4.3431 3 6 3C7.4961 3 8.7635 4.1023 8.971 5.5839L11.0097 20.1387C11.0788 20.6326 11.5013 21 12 21C12.4987 21 12.9212 20.6326 12.9903 20.1387L15.029 5.5839C15.2365 4.1023 16.5039 3 18 3C19.6569 3 21 4.3431 21 6");
}

</style>
