<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ga3lqm5lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-28-filled" /></template>
<style>
.ga3lqm5lz {
  fill: currentColor;
  d: path("M13 3v3.25A2.75 2.75 0 0 0 15.75 9H25v12.25A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zm1.5 0v3.25c0 .69.56 1.25 1.25 1.25H25v-.75A3.75 3.75 0 0 0 21.25 3z");
}

</style>
