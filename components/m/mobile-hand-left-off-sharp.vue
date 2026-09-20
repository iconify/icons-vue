<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3qz5bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-hand-left-off-sharp" /></template>
<style>
.oi3qz5bjc {
  fill: currentColor;
  d: path("m20.475 23.3l-1.3-1.3H11.6l3.45-4.125l-1.425-1.425L9.6 21.275q-.275.35-.687.538T8.05 22H7q-1.25 0-2.125-.875T4 19v-8l2.1-2.1L.7 3.5l1.4-1.4l19.8 19.8zM20 17.2L7 4.2V2h13zM14.213 6.713Q14.5 6.425 14.5 6t-.288-.712T13.5 5t-.712.288T12.5 6t.288.713T13.5 7t.713-.288M8 17.5l4.45-2.225L8 10.8z");
}

</style>
