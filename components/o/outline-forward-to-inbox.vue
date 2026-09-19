<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhf6nqb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-forward-to-inbox" /></template>
<style>
.xhf6nqb8b {
  fill: currentColor;
  d: path("M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h9v-2H4V8l8 5l8-5v5h2V6c0-1.1-.9-2-2-2m-8 7L4 6h16zm7 4l4 4l-4 4v-3h-4v-2h4z");
}

</style>
