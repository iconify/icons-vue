<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="codrdcbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-airplay" /></template>
<style>
.codrdcbyt {
  fill: currentColor;
  d: path("M6 22h12l-6-6zM23 3H1v16h6v-2H3V5h18v12h-4v2h6z");
}

</style>
