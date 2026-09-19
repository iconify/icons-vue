<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2_5g7b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-forward-to-inbox" /></template>
<style>
.m2_5g7b3c {
  fill: currentColor;
  d: path("M22 4H2v16h11v-2H4V8l8 5l8-5v5h2zm-10 7L4 6h16zm7 4l4 4l-4 4v-3h-4v-2h4z");
}

</style>
