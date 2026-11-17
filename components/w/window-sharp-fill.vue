<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zdg4fnu5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-sharp-fill" /></template>
<style>
.zdg4fnu5p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2C20.552 2 21 2.448 21 3V20H23V22H1V20H3V3C3 2.448 3.448 2 4 2H20ZM11 4V11H5V13H11V20H13V13H19V11H13V4H11Z");
}

</style>
