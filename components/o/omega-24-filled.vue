<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l15axux-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:omega-24-filled" /></template>
<style>
.l15axux-g {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10c0 2.428-1.048 4.426-2.182 5.878c-.702.9-1.456 1.614-2.063 2.122H21a1 1 0 1 1 0 2h-4.4c-.828 0-1.51-.63-1.592-1.437L15 20.399l.013-.204a1.64 1.64 0 0 1 .688-1.134l.207-.149a12.4 12.4 0 0 0 2.334-2.264C19.21 15.408 20 13.834 20 12a8 8 0 1 0-16 0c0 1.834.79 3.409 1.758 4.648a12.4 12.4 0 0 0 2.54 2.413c.424.297.702.788.702 1.338A1.6 1.6 0 0 1 7.4 22H3a1 1 0 1 1 0-2h3.245a14.2 14.2 0 0 1-2.063-2.122C3.048 16.426 2 14.428 2 12C2 6.477 6.477 2 12 2");
}

</style>
