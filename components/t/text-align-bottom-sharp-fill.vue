<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n5d2m3bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-bottom-sharp-fill" /></template>
<style>
.n5d2m3bbq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM6 12L6 14L18 14L18 12ZM6 16L6 18L14 18L14 16Z");
}

</style>
