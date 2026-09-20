<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csqw5cc0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-fields-outline-rounded" /></template>
<style>
.csqw5cc0o {
  fill: currentColor;
  d: path("M8.11 18.82q-.187-.179-.187-.435V6.25H3.635q-.265 0-.45-.184T3 5.619t.18-.441T3.615 5h9.846q.265 0 .45.18t.185.438t-.18.444t-.435.188H9.173v12.116q0 .264-.18.449T8.556 19t-.445-.18m8.875 0q-.178-.179-.178-.436v-7.23H14.48q-.265 0-.45-.184t-.185-.447t.18-.441t.436-.178h5.904q.264 0 .449.18t.185.438t-.18.444t-.435.188h-2.346v7.23q0 .257-.18.436q-.18.18-.438.18q-.257 0-.435-.18");
}

</style>
