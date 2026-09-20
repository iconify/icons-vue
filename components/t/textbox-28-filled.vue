<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t9i2orf7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-28-filled" /></template>
<style>
.t9i2orf7d {
  fill: currentColor;
  d: path("M6.75 3A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25V6.75A3.75 3.75 0 0 0 21.25 3zm2 10h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5M8 8.75A.75.75 0 0 1 8.75 8h10.5a.75.75 0 0 1 0 1.5H8.75A.75.75 0 0 1 8 8.75M8.75 18h10.5a.75.75 0 0 1 0 1.5H8.75a.75.75 0 0 1 0-1.5");
}

</style>
