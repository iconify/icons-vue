<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t4tkyrbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-off-20-regular" /></template>
<style>
.t4tkyrbpy {
  fill: currentColor;
  d: path("M17.147 2.146a.5.5 0 1 1 .707.708l-1.856 1.854a8 8 0 0 1-11.29 11.29l-1.854 1.856a.5.5 0 0 1-.708-.707zM5.416 15.29a7 7 0 0 0 9.872-9.872zM11.331 10c.2-.665 1.142-.664 1.34.001l.179.593c.08.268.29.479.558.56l.594.177c.665.2.665 1.141 0 1.34l-.594.179a.83.83 0 0 0-.558.56l-.178.592c-.2.665-1.141.666-1.34.001l-.18-.595a.83.83 0 0 0-.56-.56l-.591-.176c-.665-.2-.665-1.141 0-1.34l.593-.18a.83.83 0 0 0 .558-.557zM10 2c1.667 0 3.214.51 4.495 1.383l-.722.721a7 7 0 0 0-9.669 9.669l-.721.722A8 8 0 0 1 10 2M7.175 5.583c.275-.777 1.375-.777 1.65 0l.257.727a1 1 0 0 0 .608.608l.727.257q.105.038.19.096l-3.336 3.335a1 1 0 0 1-.096-.19l-.256-.726a1 1 0 0 0-.61-.609l-.726-.257c-.777-.275-.777-1.374 0-1.65l.727-.256a1 1 0 0 0 .609-.61z");
}

</style>
