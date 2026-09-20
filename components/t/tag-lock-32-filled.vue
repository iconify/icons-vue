<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="al3g700zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-lock-32-filled" /></template>
<style>
.al3g700zm {
  fill: currentColor;
  d: path("M15.636 3.952A3.25 3.25 0 0 1 17.934 3h7.818a3.25 3.25 0 0 1 3.25 3.25v7.818a3.25 3.25 0 0 1-.952 2.298l-.518.518a5 5 0 0 0-9.452 1.222A4 4 0 0 0 15 22v6q0 .43.088.836a3.25 3.25 0 0 1-3.314-.79l-7.818-7.818a3.25 3.25 0 0 1 0-4.596zM23 11a2 2 0 1 0 0-4a2 2 0 0 0 0 4m-3.5 8.5H19a2.5 2.5 0 0 0-2.5 2.5v6a2.5 2.5 0 0 0 2.5 2.5h8a2.5 2.5 0 0 0 2.5-2.5v-6a2.5 2.5 0 0 0-2.5-2.5h-.5V19a3.5 3.5 0 1 0-7 0zm2-.5a1.5 1.5 0 0 1 3 0v.5h-3zm3.5 6a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
