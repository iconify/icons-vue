<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8tgzv5fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-column-24-filled" /></template>
<style>
.g8tgzv5fl {
  fill: currentColor;
  d: path("M16 21h1.75A3.25 3.25 0 0 0 21 17.75V16h-5zm0-6.5h5v-5h-5zm-1.5-5v5h-5v-5zm0-1.5h-5V4.5H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75H9.5V16h5v5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3h8.25zM16 8h5V6.25A3.25 3.25 0 0 0 17.75 3H16z");
}

</style>
