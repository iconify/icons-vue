<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz4geob8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:speed-0-2x-sharp" /></template>
<style>
.sz4geob8g {
  fill: currentColor;
  d: path("M3 17v-2h2v2zm3 0v-6h4V9H6V7h6v6H8v2h4v2zm7 0l3-5l-3-5h2l2 3.325L19 7h2l-3 5l3 5h-2l-2-3.325L15 17z");
}

</style>
