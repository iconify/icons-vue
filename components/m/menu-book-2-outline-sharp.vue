<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="estkobf2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:menu-book-2-outline-sharp" /></template>
<style>
.estkobf2m {
  fill: currentColor;
  d: path("M4 22v-4H3v-2h1v-3H3v-2h1V8H3V6h1V2h16v20zm2-2h12V4H6v2h1v2H6v3h1v2H6v3h1v2H6zm3.5-3H11v-4q.65-.175 1.075-.712t.425-1.213V7h-1v3.775h-.75V7h-1v3.775H9V7H8v4.075q0 .675.425 1.213T9.5 13zm5.5 0h1.5V7q-1.25 0-2.125.875T13.5 10v3H15zm-9 3V4z");
}

</style>
