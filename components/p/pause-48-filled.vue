<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uqqdc4boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pause-48-filled" /></template>
<style>
.uqqdc4boi {
  fill: currentColor;
  d: path("M11.75 6A3.75 3.75 0 0 0 8 9.75v28.5A3.75 3.75 0 0 0 11.75 42h6.5A3.75 3.75 0 0 0 22 38.25V9.75A3.75 3.75 0 0 0 18.25 6zm18 0A3.75 3.75 0 0 0 26 9.75v28.5A3.75 3.75 0 0 0 29.75 42h6.5A3.75 3.75 0 0 0 40 38.25V9.75A3.75 3.75 0 0 0 36.25 6z");
}

</style>
