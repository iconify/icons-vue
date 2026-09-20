<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="jhudeable"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:projection-screen-28-filled" /></template>
<style>
.jhudeable {
  fill: currentColor;
  d: path("M4 3a2 2 0 0 0-1 3.732v9.518a4.25 4.25 0 0 0 4.25 4.25h6v3h-4.5a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5h-4.5v-3h6A4.25 4.25 0 0 0 25 16.25V6.732A2 2 0 0 0 24 3z");
}

</style>
