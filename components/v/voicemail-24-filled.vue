<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jib4clces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:voicemail-24-filled" /></template>
<style>
.jib4clces {
  fill: currentColor;
  d: path("M19.749 4a2.25 2.25 0 0 1 2.25 2.25v11.505a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 17.755V6.25A2.25 2.25 0 0 1 4.25 4zm-4 5H8l-.176.005a3 3 0 1 0 2.877 1.689L10.6 10.5h2.8a3 3 0 1 0 2.775-1.495L16 9l-.17.004zM8 10.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m8 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
