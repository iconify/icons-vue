<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6j6-ob9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-mode-of-travel" /></template>
<style>
.v6j6-ob9y {
  fill: currentColor;
  d: path("M4 10.2C4 5.22 7.8 2 12 2c4 0 7.64 2.92 7.97 7.5h2.32c.45 0 .67.54.35.85l-3.29 3.29c-.2.2-.51.2-.71 0l-3.29-3.29a.5.5 0 0 1 .35-.85h2.26C17.65 6.24 15.13 4 12 4c-3.35 0-6 2.57-6 6.2c0 2.34 1.95 5.44 6 9.14q.96-.885 1.77-1.71a2.5 2.5 0 0 1-.27-1.12a2.5 2.5 0 0 1 5 0a2.492 2.492 0 0 1-3.19 2.39c-.78.82-1.67 1.66-2.65 2.52c-.38.33-.95.33-1.33 0C6.45 17.12 4 13.38 4 10.2");
}

</style>
