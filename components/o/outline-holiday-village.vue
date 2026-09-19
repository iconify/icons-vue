<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atla1bcob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-holiday-village" /></template>
<style>
.atla1bcob {
  fill: currentColor;
  d: path("m8 4l-6 6v10h12V10zm4 14H9v-3H7v3H4v-7.17l4-4l4 4zm-3-5H7v-2h2zm9 7V8.35L13.65 4h-2.83L16 9.18V20zm4 0V6.69L19.31 4h-2.83L20 7.52V20z");
}

</style>
