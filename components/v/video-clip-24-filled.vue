<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgs2cybnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-24-filled" /></template>
<style>
.wgs2cybnu {
  fill: currentColor;
  d: path("M5.25 3A3.25 3.25 0 0 0 2 6.25v11.5A3.25 3.25 0 0 0 5.25 21h13.5A3.25 3.25 0 0 0 22 17.75V6.25A3.25 3.25 0 0 0 18.75 3zM9 9.25a1 1 0 0 1 1.482-.876l5 2.75a1 1 0 0 1 0 1.753l-5 2.75A1 1 0 0 1 9 14.75z");
}

</style>
