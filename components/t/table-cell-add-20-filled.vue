<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n1akj0baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-add-20-filled" /></template>
<style>
.n1akj0baz {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-5.477 4a5.48 5.48 0 0 0 1.234 4H9a2 2 0 0 1-2-2v-2zm5.477-2a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M6 13H4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h2zm7-3.792A5.51 5.51 0 0 0 9.208 13H7V7h6zM16 7a2 2 0 0 1 2 2v1.257a5.48 5.48 0 0 0-4-1.234V7zm-5-5a2 2 0 0 1 2 2v2H7V4a2 2 0 0 1 2-2z");
}

</style>
