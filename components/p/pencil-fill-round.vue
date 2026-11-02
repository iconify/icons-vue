<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjd-bfbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-fill-round" /></template>
<style>
.rjd-bfbwn {
  fill: currentColor;
  d: path("M13.414 8L12 6.586l1.293-1.293a3.828 3.828 0 0 1 5.414 5.414L17.414 12ZM3.293 15.293L10.586 8L16 13.414l-7.293 7.293A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707");
}

</style>
