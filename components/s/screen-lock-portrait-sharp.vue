<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo9fhhb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screen-lock-portrait-sharp" /></template>
<style>
.jo9fhhb1y {
  fill: currentColor;
  d: path("M9.23 15.654v-4.538h1.02v-1q0-.749.51-1.26q.511-.51 1.26-.51t1.258.51t.51 1.26v1h.981v4.538zm1.79-4.538h2v-1q0-.425-.288-.713t-.713-.288t-.712.288t-.288.713zM6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
