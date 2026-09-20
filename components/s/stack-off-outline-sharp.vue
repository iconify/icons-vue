<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht609ebqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-off-outline-sharp" /></template>
<style>
.ht609ebqz {
  fill: currentColor;
  d: path("m22 19.15l-2-2V10h-7.15l-2-2H22zM14 6V4H6.85l-2-2H16v4zm-4 14h7.15L10 12.85zm10.575 3.425L19.15 22H8V10.85l-4-4V14h2v2H2V4.85L.575 3.425L2 2l20 20zm-7-7");
}

</style>
