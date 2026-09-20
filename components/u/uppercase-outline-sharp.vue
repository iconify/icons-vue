<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2yux-nmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:uppercase-outline-sharp" /></template>
<style>
.y2yux-nmm {
  fill: currentColor;
  d: path("M16.539 17.577v-7.046l-2.1 2.1l-.708-.708l3.307-3.308l3.308 3.308l-.708.708l-2.1-2.1v7.046zm-12.385 0l3.76-10.23h1.09l3.798 10.23H11.71l-1.033-2.96h-4.43l-1.02 2.96zM6.59 13.71h3.756L8.49 8.487h-.06z");
}

</style>
