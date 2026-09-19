<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8wiv0j6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-table-restaurant" /></template>
<style>
.f8wiv0j6j {
  fill: currentColor;
  d: path("m21.96 9.73l-1.43-5a.996.996 0 0 0-.96-.73H4.43c-.45 0-.84.3-.96.73l-1.43 5c-.18.63.3 1.27.96 1.27h2.2L4 20h2l.67-5h10.67l.66 5h2l-1.2-9H21c.66 0 1.14-.64.96-1.27M6.93 13l.27-2h9.6l.27 2zm-2.6-4l.86-3h13.63l.86 3z");
}

</style>
