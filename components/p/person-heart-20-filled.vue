<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q4my_0vol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-heart-20-filled" /></template>
<style>
.q4my_0vol {
  fill: currentColor;
  d: path("M9 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-4.991 9A2 2 0 0 0 2 13c0 1.691.833 2.966 2.135 3.797C5.417 17.614 7.145 18 9 18c.955 0 1.876-.102 2.72-.313l-1.83-2.002A3.394 3.394 0 0 1 9.987 11zm10.49 1.003l-.628-.493a2.394 2.394 0 0 0-3.244 3.5l3.503 3.83a.5.5 0 0 0 .738 0l3.504-3.83a2.394 2.394 0 0 0-3.244-3.5z");
}

</style>
