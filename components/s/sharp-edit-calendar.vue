<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si5-1024p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-edit-calendar" /></template>
<style>
.si5-1024p {
  fill: currentColor;
  d: path("M12 22H3V4h3V2h2v2h8V2h2v2h3v8h-2v-2H5v10h7zm10.13-5.01l1.41-1.41l-2.12-2.12l-1.41 1.41zm-.71.71l-5.3 5.3H14v-2.12l5.3-5.3z");
}

</style>
