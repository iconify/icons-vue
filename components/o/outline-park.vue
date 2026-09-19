<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-1v_4bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-park" /></template>
<style>
.f-1v_4bkn {
  fill: currentColor;
  d: path("M17 12h2L12 2L5.05 12H7l-3.9 6h6.92v4h3.95v-4H21zM6.79 16l3.9-6H8.88l3.13-4.5l3.15 4.5h-1.9l4 6z");
}

</style>
