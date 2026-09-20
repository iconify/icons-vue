<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dty6tab4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-lamp-outline-rounded" /></template>
<style>
.dty6tab4s {
  fill: currentColor;
  d: path("M13.5 20.5q-.213 0-.356-.144T13 19.999t.144-.356t.356-.143h6q.213 0 .356.144t.144.357t-.144.356t-.356.143zM5.929 9.23h3.763V5.617q0-.27-.173-.443T9.077 5h-.898q-.192 0-.337.096q-.144.096-.22.27zm10.214 8.357Q16 17.443 16 17.231V8.077q0-.617-.441-1.059q-.442-.441-1.059-.441h-3.808v2.846q0 .343-.232.576t-.575.232h-4.25q-.454 0-.687-.364T4.902 9.1L6.7 4.97q.212-.454.604-.712T8.179 4h.898q.658 0 1.127.463q.469.462.488 1.114H14.5q1.042 0 1.77.729q.73.73.73 1.771v9.154q0 .212-.144.356t-.357.144t-.356-.144M5.93 9.231h3.763z");
}

</style>
