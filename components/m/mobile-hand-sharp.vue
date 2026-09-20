<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru9c-db-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-hand-sharp" /></template>
<style>
.ru9c-db-g {
  fill: currentColor;
  d: path("M4 22V2h13v4h-3v8.275l-3.4-1.7l-3.3 3.3L12.4 22zm11.95 0q-.45 0-.862-.187t-.688-.538L10 16l1-1l5 2.5V8h1l3 3v8q0 1.25-.875 2.125T17 22zM11.213 6.713Q11.5 6.425 11.5 6t-.288-.712T10.5 5t-.712.288T9.5 6t.288.713T10.5 7t.713-.288");
}

</style>
