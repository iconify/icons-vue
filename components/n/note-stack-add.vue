<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzqu_qdba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:note-stack-add" /></template>
<style>
.vzqu_qdba {
  fill: currentColor;
  d: path("M14 18h1v-3h3v-1h-3v-3h-1v3h-3v1h3zm-6 1.385V9.609q0-.672.475-1.14Q8.95 8 9.621 8h9.764q.666 0 1.14.475T21 9.615v6.962L16.577 21H9.615q-.666 0-1.14-.475T8 19.386M3.025 6.596q-.13-.671.257-1.212q.387-.542 1.06-.665l9.62-1.694q.67-.13 1.212.257t.665 1.06l.211 1.274H9.616q-1.65 0-2.825 1.175T5.616 9.616v7.78q-.343-.167-.582-.475q-.24-.307-.315-.705z");
}

</style>
