<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nalr3mgim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-brightness-sharp" /></template>
<style>
.nalr3mgim {
  fill: currentColor;
  d: path("m12 17.5l1.5-1.5H16v-2.5l1.5-1.5l-1.5-1.5V8h-2.5L12 6.5L10.5 8H8v2.5L6.5 12L8 13.5V16h2.5zm0-2.5V9q1.25 0 2.125.875T15 12t-.875 2.125T12 15M2 20V4h20v16z");
}

</style>
