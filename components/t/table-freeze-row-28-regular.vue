<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="um_piro9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-row-28-regular" /></template>
<style>
.um_piro9r {
  fill: currentColor;
  d: path("M25 6.75A3.75 3.75 0 0 0 21.25 3H6.75A3.75 3.75 0 0 0 3 6.75v14.5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25zM4.5 11h5v6h-5zM17 17h-6v-6h6zM4.5 18.5h5v5H6.75a2.25 2.25 0 0 1-2.25-2.25zm12.5 5h-6v-5h6zm6.5-2.25a2.25 2.25 0 0 1-2.25 2.25H18.5v-5h5zm0-10.25v6h-5v-6zm-19-4.25A2.25 2.25 0 0 1 6.75 4.5h14.5a2.25 2.25 0 0 1 2.25 2.25V9.5h-19z");
}

</style>
