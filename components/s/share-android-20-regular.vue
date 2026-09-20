<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wdy61ob_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-android-20-regular" /></template>
<style>
.wdy61ob_m {
  fill: currentColor;
  d: path("M12 5.502a2.502 2.502 0 1 1 .531 1.541L7.915 9.351a2.5 2.5 0 0 1 0 1.297l4.618 2.31a2.5 2.5 0 1 1-.448.894l-4.618-2.31a2.5 2.5 0 1 1 0-3.086l4.618-2.307A2.5 2.5 0 0 1 12 5.502M14.502 4a1.501 1.501 0 1 0 0 3.003a1.501 1.501 0 0 0 0-3.003m-.002 9a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M4 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0");
}

</style>
