<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mptm2iblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-circle-24-filled" /></template>
<style>
.mptm2iblq {
  fill: currentColor;
  d: path("M12 22C6.477 22 2 17.523 2 12S6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10m5-8.5a1.5 1.5 0 0 0-1.5-1.5h-7A1.5 1.5 0 0 0 7 13.5v.5c0 1.971 1.86 4 5 4s5-2.029 5-4zm-2.25-5.25a2.75 2.75 0 1 0-5.5 0a2.75 2.75 0 0 0 5.5 0");
}

</style>
