<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mob8gmb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-24-filled" /></template>
<style>
.mob8gmb2z {
  fill: currentColor;
  d: path("M6 4a1 1 0 0 0 1 1h14a1 1 0 1 0 0-2H7a1 1 0 0 0-1 1m7 5a1 1 0 0 0 1 1h7a1 1 0 1 0 0-2h-7a1 1 0 0 0-1 1m-6 9h14a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2m6-4a1 1 0 0 0 1 1h7a1 1 0 1 0 0-2h-7a1 1 0 0 0-1 1m-2-2.5a4.5 4.5 0 1 0-9 0a4.5 4.5 0 0 0 9 0m-2 0a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1 0-1h4a.5.5 0 0 1 .5.5");
}

</style>
