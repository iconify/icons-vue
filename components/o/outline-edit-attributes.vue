<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4hvzfbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-edit-attributes" /></template>
<style>
.m4hvzfbbc {
  fill: currentColor;
  d: path("M17.63 7H6.37C3.96 7 2 9.24 2 12s1.96 5 4.37 5h11.26c2.41 0 4.37-2.24 4.37-5s-1.96-5-4.37-5m0 8H6.37C5.09 15 4 13.63 4 12s1.09-3 2.37-3h11.26C18.91 9 20 10.37 20 12s-1.09 3-2.37 3M7.24 13.06l-1.87-1.87l-.7.7l2.57 2.57l4.22-4.22l-.7-.7z");
}

</style>
