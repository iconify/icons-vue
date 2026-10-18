<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wukxe0lmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:nfc-two-tone" /></template>
<style>
.wukxe0lmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.2729 2C18.6731 4.7501 20 8.3104 20 12C20 15.6896 18.6731 19.2499 16.2729 22M12 4C13.9319 6.2001 15 9.0483 15 12C15 14.9517 13.9319 17.7999 12 20M8 7C9.288 8.3751 10 10.1552 10 12C10 13.8448 9.288 15.6249 8 17M4 9C4.644 9.825 5 10.8931 5 12C5 13.1069 4.644 14.175 4 15");
}

</style>
