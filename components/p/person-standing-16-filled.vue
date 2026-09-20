<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o4hlnvp7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-standing-16-filled" /></template>
<style>
.o4hlnvp7r {
  fill: currentColor;
  d: path("M7.5 4.5a1.75 1.75 0 1 0 .001-3.499A1.75 1.75 0 0 0 7.5 4.5m3.5 2v3c0 .551-.448 1-1 1V14a1 1 0 0 1-2 0v-3a.5.5 0 0 0-1 0v3a1 1 0 0 1-2 0v-3.5c-.552 0-1-.449-1-1v-3c0-.916.623-1.682 1.464-1.918A2.74 2.74 0 0 0 7.5 5.5c.81 0 1.532-.359 2.036-.918A2 2 0 0 1 11 6.5");
}

</style>
