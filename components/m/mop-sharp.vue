<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5c-5fxub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mop-sharp" /></template>
<style>
.h5c-5fxub {
  fill: currentColor;
  d: path("M3.55 21H6v-3h2v3h3v-3h2v3h3v-3h2v3h2.45l-1-4H4.55zM1 23l2-8v-4h6V4q0-1.25.875-2.125T12 1t2.125.875T15 4v7h6v4l2 8z");
}

</style>
