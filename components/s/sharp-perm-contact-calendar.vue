<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt6p5gmed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-perm-contact-calendar" /></template>
<style>
.vt6p5gmed {
  fill: currentColor;
  d: path("M21 3h-3V1h-2v2H8V1H6v2H3v18h18zm-9 3c1.66 0 3 1.34 3 3s-1.34 3-3 3s-3-1.34-3-3s1.34-3 3-3m6 12H6v-1c0-2 4-3.1 6-3.1s6 1.1 6 3.1z");
}

</style>
