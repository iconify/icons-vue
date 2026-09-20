<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n1htgdbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-lock-16-filled" /></template>
<style>
.n1htgdbxh {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2H5v3H2zM6 5V2h4v3zM2 6h3v4H2zm4 0v4h1a2 2 0 0 1 1.5-1.937V8c0-.768.289-1.47.764-2zm1 5v3H6v-3zm-5 0h3v3h-.5A2.5 2.5 0 0 1 2 11.5zm12-6.5V5h-3V2h.5A2.5 2.5 0 0 1 14 4.5M9.5 8v1H9a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1h-.5V8a2 2 0 1 0-4 0m1 1V8a1 1 0 1 1 2 0v1zm1 2.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
