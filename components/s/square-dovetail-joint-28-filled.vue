<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g8fou3bsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-dovetail-joint-28-filled" /></template>
<style>
.g8fou3bsk {
  fill: currentColor;
  d: path("M10 16.796a.75.75 0 0 1 .957-.721l5.543 1.589v-7.328l-5.543 1.589a.75.75 0 0 1-.957-.721V3H6.75A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25H10zM21.25 3H11.5v7.209l5.543-1.589a.75.75 0 0 1 .957.721v9.318a.75.75 0 0 1-.957.721L11.5 17.791V25h9.75A3.75 3.75 0 0 0 25 21.25V6.75A3.75 3.75 0 0 0 21.25 3");
}

</style>
