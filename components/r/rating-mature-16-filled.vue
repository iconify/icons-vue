<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c4vre3jnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rating-mature-16-filled" /></template>
<style>
.c4vre3jnw {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zm3.924.735A.5.5 0 0 0 5 5.5v5a.5.5 0 1 0 1 0V7.243l1.576 2.522a.5.5 0 0 0 .848 0L10 7.243V10.5a.5.5 0 1 0 1 0v-5a.5.5 0 0 0-.924-.265L8 8.557z");
}

</style>
