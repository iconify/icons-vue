<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9eymvw8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:window-sharp" /></template>
<style>
.q9eymvw8t {
  fill: currentColor;
  d: path("M12.5 12.5H20V20h-7.5zm0-1V4H20v7.5zm-1 0H4V4h7.5zm0 1V20H4v-7.5z");
}

</style>
