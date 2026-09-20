<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6lds4b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:night-shelter-outline" /></template>
<style>
.t6lds4b7m {
  fill: currentColor;
  d: path("M7 18h1v-1.5h8V18h1v-4q0-.825-.587-1.412T15 12h-3.5v3.5H8V11H7zm3.638-3.363q.362-.362.362-.887t-.363-.888t-.887-.362t-.888.363t-.362.887t.363.888t.887.362t.888-.363M4 21V9l8-6l8 6v12zm2-2h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
