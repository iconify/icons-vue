<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onumwmbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-thumb-down-off-alt" /></template>
<style>
.onumwmbhr {
  fill: currentColor;
  d: path("M19 3h4v12h-4zM1 11.6V16h8.31l-1.12 5.38L9.83 23L17 15.82V3H4.69zM15 5v9.99l-4.34 4.35l.61-2.93l.5-2.41H3v-1.99L6.01 5z");
}

</style>
