<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhvrpqw8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:whiteboard" /></template>
<style>
.rhvrpqw8i {
  fill: currentColor;
  d: path("M5 18v-5l9.95-9.95Q16 2 17.45 2t2.5 1.05Q21 4.1 21 5.55t-1.05 2.5L10 18Zm2-2h2.175l9.375-9.375q.45-.45.45-1.088q0-.637-.45-1.087Q18.1 4 17.462 4q-.637 0-1.087.45L7 13.825Zm-4 6v-2h18v2Z");
}

</style>
