<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbta1ez1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-local-printshop" /></template>
<style>
.zbta1ez1s {
  fill: currentColor;
  d: path("M18 7V4c0-.55-.45-1-1-1H7c-.55 0-1 .45-1 1v3zm1 1H5c-1.66 0-3 1.34-3 3v5c0 .55.45 1 1 1h3v2c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2v-2h3c.55 0 1-.45 1-1v-5c0-1.66-1.34-3-3-3m-3 11H8v-4h8zm2-6.5c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

</style>
