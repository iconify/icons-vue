<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyt1oubps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-offset-24-filled" /></template>
<style>
.lyt1oubps {
  fill: currentColor;
  d: path("M14 3H6.25A3.25 3.25 0 0 0 3 6.25V8.5h11zm1.5 5.5H21V6.25A3.25 3.25 0 0 0 17.75 3H15.5zM21 10H10v4h11zM8.5 10H3v4h5.5zM3 17.75V15.5h11V21H6.25A3.25 3.25 0 0 1 3 17.75M15.5 21v-5.5H21v2.25A3.25 3.25 0 0 1 17.75 21z");
}

</style>
