<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x7pkhu1sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:notebook-subsection-20-regular" /></template>
<style>
.x7pkhu1sm {
  fill: currentColor;
  d: path("M4 5.5A3.5 3.5 0 0 1 7.5 2H10c.818 0 1.544.393 2 1H7.5A2.5 2.5 0 0 0 5 5.5V15a2.5 2.5 0 0 1-1-2zm9.432-3.495L13.5 2c.253 0 .462.226.495.519L14 2.6v14.8c0 .331-.224.6-.5.6c-.253 0-.462-.226-.495-.519L13 17.4V17H8a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h5V2.6c0-.304.188-.555.432-.595M8 5a1 1 0 0 0-1 1v9a1 1 0 0 0 1 1h5V5z");
}

</style>
