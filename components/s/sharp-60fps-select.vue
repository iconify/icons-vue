<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d31b_bchp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-60fps-select" /></template>
<style>
.d31b_bchp {
  fill: currentColor;
  d: path("M18 6v6h-3V6zm2-2h-7v10h7zm-9 2V4H4v10h7V8H6V6zm-2 4v2H6v-2zM5 22H3v-5h2zm4 0H7v-5h2zm4 0h-2v-5h2zm8 0h-6v-5h6z");
}

</style>
