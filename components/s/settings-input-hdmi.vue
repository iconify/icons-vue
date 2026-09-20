<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-0xa9s9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settings-input-hdmi" /></template>
<style>
.n-0xa9s9b {
  fill: currentColor;
  d: path("M8 22v-3l-3-6V7h1V4q0-.825.588-1.412T8 2h8q.825 0 1.413.588T18 4v3h1v6l-3 6v3zM8 7h2V5h1v2h2V5h1v2h2V4H8z");
}

</style>
