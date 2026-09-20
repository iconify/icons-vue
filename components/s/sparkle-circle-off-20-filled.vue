<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hwciu7_0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-off-20-filled" /></template>
<style>
.hwciu7_0k {
  fill: currentColor;
  d: path("M17.147 2.146a.5.5 0 1 1 .707.708l-1.856 1.854a8 8 0 0 1-11.29 11.29l-1.854 1.856a.5.5 0 0 1-.708-.707zM12.67 10c-.2-.665-1.141-.666-1.34-.001l-.18.595a.83.83 0 0 1-.558.557l-.593.18c-.665.199-.665 1.14.001 1.34l.592.177a.83.83 0 0 1 .558.56l.18.594c.199.665 1.14.664 1.34-.001l.178-.593a.84.84 0 0 1 .56-.56l.593-.177c.664-.2.664-1.141 0-1.34l-.594-.179a.84.84 0 0 1-.56-.56zM10 2c1.667 0 3.214.51 4.495 1.383L10.607 7.27a1 1 0 0 0-.19-.096l-.727-.257a1 1 0 0 1-.608-.608l-.257-.727c-.275-.777-1.375-.777-1.65 0l-.256.726a1 1 0 0 1-.61.609l-.726.257c-.777.275-.777 1.374 0 1.65l.727.256a1 1 0 0 1 .609.61l.256.725a1 1 0 0 0 .096.19l-3.888 3.89A8 8 0 0 1 10 2");
}

</style>
