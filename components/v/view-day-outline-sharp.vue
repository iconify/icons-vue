<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwl_lt3ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-day-outline-sharp" /></template>
<style>
.cwl_lt3ia {
  fill: currentColor;
  d: path("M3 20v-2h18v2zm0-4V8h18v8zm2-2h14v-4H5zM3 6V4h18v2zm2 8v-4z");
}

</style>
