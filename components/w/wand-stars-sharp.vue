<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujs6wb97f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wand-stars-sharp" /></template>
<style>
.ujs6wb97f {
  fill: currentColor;
  d: path("M4.708 20L4 19.292l7.736-7.742l-4.217-1.029L11.7 7.927L11.333 3l3.763 3.179l4.554-1.854l-1.829 4.56L21 12.641l-4.927-.342l-2.6 4.18l-1.048-4.216zm.58-13.192L4 5.519l1.289-1.288l1.288 1.288zM18.482 20l-1.289-1.288l1.289-1.289l1.288 1.289z");
}

</style>
