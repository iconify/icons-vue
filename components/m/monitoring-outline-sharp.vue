<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r40sfdbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:monitoring-outline-sharp" /></template>
<style>
.r40sfdbna {
  fill: currentColor;
  d: path("M3.5 20.5v-1.288l1-1V20.5zm4 0v-5.288l1-1V20.5zm4 0v-6.288l1 1.025V20.5zm4 0v-5.263l1-1V20.5zm4 0v-9.288l1-1V20.5zm-16-5.886V13.21l6.5-6.5l4 4l6.5-6.5v1.403l-6.5 6.5l-4-4z");
}

</style>
