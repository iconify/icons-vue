<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a4qou9i7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-background-effect-horizontal-48-filled" /></template>
<style>
.a4qou9i7b {
  fill: currentColor;
  d: path("M4.374 10.5A4.25 4.25 0 0 1 8.248 8h31.5a4.25 4.25 0 0 1 3.874 2.5zm39.625 5H30.615a8 8 0 0 1 1.133 2.5h12.251zM4 15.5h13.385a8 8 0 0 0-1.133 2.5H4zm0 7.25h12.485a8 8 0 0 0 1.479 2.5H4zM4 30h8.15c-.098.4-.15.82-.15 1.25v1.25H4zm32 1.25v1.25h7.999V30H35.85c.098.4.15.82.15 1.25M4.375 37.5H12V40H8.25a4.25 4.25 0 0 1-3.875-2.5M36 37.5V40h3.75a4.25 4.25 0 0 0 3.873-2.5zm-4.485-14.75a8 8 0 0 1-1.479 2.5H44v-2.5zM14 40v-8.75A3.25 3.25 0 0 1 17.25 28h13.5A3.25 3.25 0 0 1 34 31.25V40zm16-20a6 6 0 1 1-12 0a6 6 0 0 1 12 0");
}

</style>
