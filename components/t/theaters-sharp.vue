<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td6nl9pru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:theaters-sharp" /></template>
<style>
.td6nl9pru {
  fill: currentColor;
  d: path("M4 21V3h2v2h2V3h8v2h2V3h2v18h-2v-2h-2v2H8v-2H6v2zm2-4h2v-2H6zm0-4h2v-2H6zm0-4h2V7H6zm10 8h2v-2h-2zm0-4h2v-2h-2zm0-4h2V7h-2z");
}

</style>
