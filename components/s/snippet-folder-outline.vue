<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e335fcbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:snippet-folder-outline" /></template>
<style>
.e335fcbut {
  fill: currentColor;
  d: path("M14.5 15.5v-5h1.375l1.625 1.625V15.5zM13 17h6v-5.5L16.5 9H13zm-9 3q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20zm0-2h16V8h-8.825l-2-2H4zm0 0V6z");
}

</style>
