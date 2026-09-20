<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnddhtbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:near-me-disabled" /></template>
<style>
.qnddhtbsr {
  fill: currentColor;
  d: path("m13.13 19.346l-2.426-6.088l-6.089-2.466l-.038-.63L9.664 8.24L4.166 2.743l.713-.713L21.97 19.12l-.713.714l-5.556-5.556l-1.94 5.067zm3.757-8.14l-4.15-4.131l6.686-2.536z");
}

</style>
