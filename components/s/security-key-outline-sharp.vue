<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt7ki5bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:security-key-outline-sharp" /></template>
<style>
.mt7ki5bor {
  fill: currentColor;
  d: path("M8 23v-5H6V1h12v17h-2v5zm4-10.5q1.25 0 2.125-.875T15 9.5t-.875-2.125T12 6.5t-2.125.875T9 9.5t.875 2.125T12 12.5M10 21h4v-3h-4zm-2-5h8V3H8zm4-5.5q-.425 0-.712-.288T11 9.5t.288-.712T12 8.5t.713.288T13 9.5t-.288.713T12 10.5M8 16h8z");
}

</style>
