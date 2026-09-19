<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgx-x_b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add-to-queue" /></template>
<style>
.lgx-x_b_a {
  fill: currentColor;
  d: path("M23 3H1v16h7v2h8v-2h7zm-2 14H3V5h18zm-5-7v2h-3v3h-2v-3H8v-2h3V7h2v3z");
}

</style>
