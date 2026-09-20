<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zgo7-ur4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pint-glass-bold" /></template>
<style>
.zgo7-ur4u {
  fill: currentColor;
  d: path("M209 24a12 12 0 0 0-9-4H56a12 12 0 0 0-11.91 13.43l23.15 193A20 20 0 0 0 87.1 244h81.8a20 20 0 0 0 19.86-17.62l23.15-192.95A12 12 0 0 0 209 24m-22.53 20l-1.92 16H71.45l-1.92-16Zm-21.12 176h-74.7L74.33 84h107.34Z");
}

</style>
