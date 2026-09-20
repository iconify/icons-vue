<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utmjmyuol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-column-and-row-dismiss-24-filled" /></template>
<style>
.utmjmyuol {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.25-9A3.25 3.25 0 0 1 21 6.25v5.774a6.47 6.47 0 0 0-5-.848V9.5h3.5V6.25a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75H9.5V16h1.676a6.47 6.47 0 0 0 .849 5H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm2.104 12.147a.5.5 0 0 0-.707 0L17.5 16.793l-1.646-1.646a.5.5 0 1 0-.707.707l1.646 1.646l-1.646 1.646a.5.5 0 1 0 .707.707l1.646-1.646l1.646 1.646a.5.5 0 1 0 .707-.707L18.208 17.5l1.646-1.646a.5.5 0 0 0 0-.707M14.5 11.733a6.53 6.53 0 0 0-2.767 2.767H9.5v-5h5z");
}

</style>
