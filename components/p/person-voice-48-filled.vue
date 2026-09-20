<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hc87mabvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-voice-48-filled" /></template>
<style>
.hc87mabvn {
  fill: currentColor;
  d: path("M32.75 28A4.25 4.25 0 0 1 37 32.249V33c0 3.755-1.942 6.567-4.92 8.38C29.151 43.163 25.214 44 21 44s-8.151-.837-11.08-2.62C6.942 39.567 5 36.755 5 33v-.751A4.25 4.25 0 0 1 9.25 28zM21 4c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10S15.477 4 21 4m18.294.122a1.25 1.25 0 0 1 1.66.606A21.9 21.9 0 0 1 43 14c0 3.31-.734 6.453-2.046 9.272a1.25 1.25 0 1 1-2.266-1.055A19.4 19.4 0 0 0 40.5 14c0-2.938-.65-5.722-1.812-8.218a1.25 1.25 0 0 1 .606-1.66m-4.924 3.52a1.25 1.25 0 0 1 1.61.73A16 16 0 0 1 37 14c0 1.98-.362 3.876-1.02 5.627a1.25 1.25 0 0 1-2.34-.879c.554-1.476.86-3.076.86-4.748s-.305-3.273-.86-4.749a1.25 1.25 0 0 1 .73-1.61");
}

</style>
