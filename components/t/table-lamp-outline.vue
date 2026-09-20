<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azz5my5yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-lamp-outline" /></template>
<style>
.azz5my5yx {
  fill: currentColor;
  d: path("M13 20.5v-1h7v1zM5.929 9.23h3.763V5.617q0-.27-.173-.443T9.077 5h-.898q-.192 0-.337.096q-.144.096-.22.27zM16 17.73V8.078q0-.617-.441-1.059q-.442-.441-1.059-.441h-3.808v2.846q0 .343-.232.576t-.575.232h-4.25q-.454 0-.687-.364T4.902 9.1L6.7 4.97q.212-.454.604-.712T8.179 4h.898q.658 0 1.127.463q.469.462.488 1.114H14.5q1.042 0 1.77.729q.73.73.73 1.771v9.654zM5.929 9.23h3.763z");
}

</style>
