<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7fczphpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-new-off-sharp" /></template>
<style>
.u7fczphpm {
  fill: currentColor;
  d: path("M19.833 21.26L18.573 20H4V5.427l-1.26-1.26l.714-.713l17.092 17.092zM17.573 19l-5.933-5.933l-1.902 1.902l-.707-.708l1.902-1.902L5 6.427V19zM7.811 5l-1-1h4.42v1zm5.948 5.948l-.707-.707L18.292 5H14V4h6v6h-1V5.708zM20 17.188l-1-1V12.77h1z");
}

</style>
