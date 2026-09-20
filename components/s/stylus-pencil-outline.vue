<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3mu44d8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stylus-pencil-outline" /></template>
<style>
.z3mu44d8d {
  fill: currentColor;
  d: path("m4 21l.55-1.625q.2-.625.725-1T6.45 18h11.1q.65 0 1.175.375t.725 1L20 21zm2-5l5-13h2l5 13zm2.9-2h6.2L12 5.975zm0 0h6.2z");
}

</style>
