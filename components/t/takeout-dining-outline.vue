<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9zrmebrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:takeout-dining-outline" /></template>
<style>
.p9zrmebrw {
  fill: currentColor;
  d: path("M7.8 18h8.45l.475-7H7.3zm-.65-9h9.725l.075-1.25L14.15 5h-4.3l-2.8 2.75zm-1.9 1.7L2 7.45l1.4-1.4L5 7.65l-.05-.6L9 3h6l4.05 4.05l-.05.6l1.6-1.6l1.4 1.4l-3.25 3.25zm.7 9.3l-.7-9.3h13.5l-.7 9.3zm6.075-9");
}

</style>
