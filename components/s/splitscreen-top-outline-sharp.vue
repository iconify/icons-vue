<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udax7gwxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:splitscreen-top-outline-sharp" /></template>
<style>
.udax7gwxi {
  fill: currentColor;
  d: path("M3 11V3h18v8zm0 10v-8h18v8zm2-2h14v-4H5z");
}

</style>
