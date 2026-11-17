<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgxujfd9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-vacuum-fill-round" /></template>
<style>
.rgxujfd9l {
  fill: currentColor;
  d: path("M4.968 4.968c3.884-3.884 10.181-3.885 14.065-.001s3.884 10.182 0 14.066s-10.182 3.884-14.066 0s-3.883-10.181.001-14.065M6.528 12c-.003.85.195 1.688.578 2.447a1 1 0 1 0 1.788-.894a3.473 3.473 0 1 1 6.212 0a1 1 0 1 0 1.788.894a5.471 5.471 0 0 0-6.87-7.55A5.47 5.47 0 0 0 6.528 12m5.482 3H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
