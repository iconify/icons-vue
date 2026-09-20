<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="uwgu6g34z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-bottom-28-filled" /></template>
<style>
.uwgu6g34z {
  fill: currentColor;
  d: path("M14.25 20c.69 0 1.25.56 1.25 1.25V25H6.75A3.75 3.75 0 0 1 3 21.25V20zm7-17A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H17v-3.75a2.75 2.75 0 0 0-2.75-2.75H3V6.75A3.75 3.75 0 0 1 6.75 3z");
}

</style>
