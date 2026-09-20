<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kqsp7es3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tab-desktop-bottom-28-regular" /></template>
<style>
.kqsp7es3u {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zM6.75 4.5A2.25 2.25 0 0 0 4.5 6.75V18.5h9.75A2.75 2.75 0 0 1 17 21.25v2.25h4.25a2.25 2.25 0 0 0 2.25-2.25V6.75a2.25 2.25 0 0 0-2.25-2.25zM4.5 21.25a2.25 2.25 0 0 0 2.25 2.25h8.75v-2.25c0-.69-.56-1.25-1.25-1.25H4.5z");
}

</style>
