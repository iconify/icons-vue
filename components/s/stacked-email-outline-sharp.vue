<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okh-4ob0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stacked-email-outline-sharp" /></template>
<style>
.okh-4ob0g {
  fill: currentColor;
  d: path("M5 17V3h18v14zm9-4.725l-7-4.85V15h14V7.425zm0-2.425L21 5H7zM1 21V6.5h2V19h16.5v2zM21 5H7z");
}

</style>
