<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys12mhbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-left-outline-sharp" /></template>
<style>
.ys12mhbrl {
  fill: currentColor;
  d: path("M15.52 19v-8.5H5.915l2.1 2.1l-.708.708L4 10l3.308-3.308l.708.708l-2.1 2.1h10.603V19z");
}

</style>
