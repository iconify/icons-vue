<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mnhw-0b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-open-sharp-fill" /></template>
<style>
.mnhw-0b_d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2C20.552 2 21 2.448 21 3V20H23V22H1V20H3V3C3 2.448 3.448 2 4 2H20ZM5 14V20H19V14H5ZM11 4V12H13V4H11Z");
}

</style>
