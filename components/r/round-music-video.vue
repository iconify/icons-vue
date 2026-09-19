<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_5gu2b4c"/><path class="hdeeh2bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-music-video" /></template>
<style>
.hdeeh2bec {
  fill: currentColor;
  d: path("M10.84 16.98c1.26-.17 2.16-1.33 2.16-2.6V9h2c.55 0 1-.45 1-1s-.45-1-1-1h-2c-.55 0-1 .45-1 1v4.51c-.46-.35-1.02-.54-1.66-.51c-1.11.07-2.09.92-2.3 2.02a2.512 2.512 0 0 0 2.8 2.96");
}

.y_5gu2b4c {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H4V6h16z");
}

</style>
