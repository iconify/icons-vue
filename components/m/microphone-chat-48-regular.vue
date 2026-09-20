<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gd5iqpotb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-48-regular" /></template>
<style>
.gd5iqpotb {
  fill: currentColor;
  d: path("M43.75 25.75c.69 0 1.25.56 1.25 1.25c0 6.205-4.71 11.31-10.75 11.935v3.815a1.25 1.25 0 1 1-2.5 0v-3.815C25.71 38.31 21 33.206 21 27a1.25 1.25 0 1 1 2.5 0a9.5 9.5 0 0 0 19 0c0-.69.56-1.25 1.25-1.25M20 4c4.195 0 8.012 1.615 10.865 4.256a9 9 0 0 0-2.586 1.08A13.44 13.44 0 0 0 20 6.5C12.544 6.5 6.5 12.544 6.5 20c0 2.238.544 4.345 1.505 6.2c.14.27.176.583.102.878l-1.604 6.42l6.42-1.605c.296-.074.61-.038.88.102a13.43 13.43 0 0 0 6.79 1.49a14 14 0 0 0 1.565 2.368A16 16 0 0 1 20 36c-2.476 0-4.822-.564-6.917-1.57L7.11 35.925c-1.83.457-3.49-1.202-3.033-3.032L5.57 26.92A15.94 15.94 0 0 1 4 20c0-8.837 7.163-16 16-16m13 6a7 7 0 0 1 7 7v10a7 7 0 1 1-14 0V17a7 7 0 0 1 7-7m0 2.5a4.5 4.5 0 0 0-4.5 4.5v10a4.5 4.5 0 1 0 9 0V17a4.5 4.5 0 0 0-4.5-4.5");
}

</style>
