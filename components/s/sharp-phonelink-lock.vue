<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijsh6izbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phonelink-lock" /></template>
<style>
.ijsh6izbn {
  fill: currentColor;
  d: path("M21 1H7v5h2V4h10v16H9v-2H7v5h14zM10.8 11V9.5C10.8 8.1 9.4 7 8 7S5.2 8.1 5.2 9.5V11H4v6h8v-6zm-1.3 0h-3V9.5c0-.8.7-1.3 1.5-1.3s1.5.5 1.5 1.3z");
}

</style>
