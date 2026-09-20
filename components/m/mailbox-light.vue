<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ssomq6bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:mailbox-light" /></template>
<style>
.ssomq6bcu {
  fill: currentColor;
  d: path("M102 152a6 6 0 0 1-6 6H56a6 6 0 0 1 0-12h40a6 6 0 0 1 6 6m136-36v60a14 14 0 0 1-14 14h-90v34a6 6 0 0 1-12 0v-34H32a14 14 0 0 1-14-14v-60a58.07 58.07 0 0 1 58-58h78V24a6 6 0 0 1 6-6h32a6 6 0 0 1 0 12h-26v28h14a58.07 58.07 0 0 1 58 58m-116 62v-62a46 46 0 0 0-92 0v60a2 2 0 0 0 2 2Zm104-62a46.06 46.06 0 0 0-46-46h-14v74a6 6 0 0 1-12 0V70h-42.71A57.93 57.93 0 0 1 134 116v62h90a2 2 0 0 0 2-2Z");
}

</style>
