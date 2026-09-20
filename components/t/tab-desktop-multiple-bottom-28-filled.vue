<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gdy6lgzqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-multiple-bottom-28-filled" /></template>
<style>
.gdy6lgzqh {
  fill: currentColor;
  d: path("M10.75 21c.69 0 1.25.56 1.25 1.25V26H5.75A3.75 3.75 0 0 1 2 22.25V21zm6.5-14A3.75 3.75 0 0 1 21 10.75v11.5A3.75 3.75 0 0 1 17.25 26H13.5v-3.75a2.75 2.75 0 0 0-2.75-2.75H2v-8.75A3.75 3.75 0 0 1 5.75 7zm3-5A5.75 5.75 0 0 1 26 7.75v9.5A3.75 3.75 0 0 1 22.25 21H22V10.75A4.75 4.75 0 0 0 17.25 6H7v-.25A3.75 3.75 0 0 1 10.75 2z");
}

</style>
