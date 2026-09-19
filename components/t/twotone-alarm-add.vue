<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ossfmhh8l"/><path class="ry0paq2ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-alarm-add" /></template>
<style>
.ossfmhh8l {
  fill: currentColor;
  d: path("M12 6c-3.86 0-7 3.14-7 7s3.14 7 7 7s7-3.14 7-7s-3.14-7-7-7m4 8h-3v3h-2v-3H8v-2h3V9h2v3h3z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ry0paq2ln {
  fill: currentColor;
  d: path("m17.337 1.81l4.607 3.845l-1.28 1.535l-4.61-3.843zm-10.674 0l1.282 1.536L3.337 7.19l-1.28-1.536zM12 4a9 9 0 1 0 .001 18.001A9 9 0 0 0 12 4m0 16c-3.86 0-7-3.14-7-7s3.14-7 7-7s7 3.14 7 7s-3.14 7-7 7m1-11h-2v3H8v2h3v3h2v-3h3v-2h-3z");
}

</style>
