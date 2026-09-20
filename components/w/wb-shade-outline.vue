<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czaoy8bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wb-shade-outline" /></template>
<style>
.czaoy8bim {
  fill: currentColor;
  d: path("m19.25 19.23l-5.308-5.307v-1.346l6.654 6.654zm-5.308 0V17l2.231 2.23zm-9.23 0V9.617H3.404l4.538-4.539l4.539 4.539h-1.308v9.615zm1.692-4.691H9.48V9.615H6.404z");
}

</style>
