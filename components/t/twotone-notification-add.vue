<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db91o4b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-notification-add" /></template>
<style>
.db91o4b-n {
  fill: currentColor;
  d: path("M16 14v3H8v-7c0-2.21 1.79-4 4-4c.85 0 1.64.26 2.28.72l1.43-1.43A5.9 5.9 0 0 0 13.5 4.2v-.7c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.7C7.91 4.86 6 7.21 6 10v7H4v2h16v-2h-2v-3zm-4 8c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2M24 8h-3V5h-2v3h-3v2h3v3h2v-3h3z");
}

</style>
