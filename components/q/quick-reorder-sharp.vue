<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0kq5sa6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:quick-reorder-sharp" /></template>
<style>
.v0kq5sa6r {
  fill: currentColor;
  d: path("M1 20v-2h5v-2H2v-2h4v-2H3.05v-2H6V7.05l-1.95-4.2L5.85 2L8.2 7h11.6l-1.95-4.15l1.8-.85L22 7v13zm11-7h4q.425 0 .713-.288T17 12t-.288-.712T16 11h-4q-.425 0-.712.288T11 12t.288.713T12 13");
}

</style>
