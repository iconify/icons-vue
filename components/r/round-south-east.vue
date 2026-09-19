<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9k83bbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-south-east" /></template>
<style>
.p9k83bbyc {
  fill: currentColor;
  d: path("M18 9c-.56 0-1 .45-1 1v5.59L6.12 4.7a.996.996 0 1 0-1.41 1.41L15.59 17H10c-.55 0-1 .45-1 1s.45 1 1 1h8c.55 0 1-.45 1-1v-8c0-.55-.45-1-1-1");
}

</style>
