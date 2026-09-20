<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="chnye0v7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-feedback-28-filled" /></template>
<style>
.chnye0v7w {
  fill: currentColor;
  d: path("M17.75 14c-.13 0-.27-.02-.4-.06a1.25 1.25 0 0 1-.85-1.19v-1.76c-1.4-.13-2.5-1.31-2.5-2.74v-3.5C14 3.23 15.23 2 16.75 2h6.5C24.77 2 26 3.23 26 4.75v3.5C26 9.77 24.77 11 23.25 11h-2.62l-1.88 2.5c-.24.32-.61.5-1 .5M9.5 16.5a4.26 4.26 0 0 1-4.25-4.25A4.26 4.26 0 0 1 9.5 8a4.26 4.26 0 0 1 4.25 4.25A4.26 4.26 0 0 1 9.5 16.5m-6.029 7.42C4.781 25.3 6.811 26 9.501 26s4.72-.7 6.03-2.08c1.522-1.61 1.473-3.553 1.47-3.684v-.006c0-1.23-1-2.23-2.23-2.23H4.231c-1.23 0-2.23 1-2.23 2.19v.013c-.004.19-.042 2.117 1.47 3.717");
}

</style>
