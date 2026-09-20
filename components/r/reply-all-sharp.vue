<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp8tsy48z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:reply-all-sharp" /></template>
<style>
.wp8tsy48z {
  fill: currentColor;
  d: path("M8.308 16.308L3 11l5.308-5.308l.713.708l-4.6 4.6l4.6 4.6zM20 18v-3q0-1.442-1.029-2.471T16.5 11.5H9.037l4.1 4.1l-.714.708L7.116 11l5.307-5.308l.714.708l-4.1 4.1H16.5q1.864 0 3.182 1.318T21 15v3z");
}

</style>
