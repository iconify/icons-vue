<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai69isbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:podium-outline-sharp" /></template>
<style>
.ai69isbex {
  fill: currentColor;
  d: path("M11.913 5.913q-.588.587-1.413.587q-.325 0-.6-.088t-.55-.287q-.6.2-.962.725T8.025 8H21l-1 7h-4.9v-2h3.175l.425-3H5.3l.425 3H8.9v2H4L3 8h3q0-1.225.675-2.225T8.5 4.3q.075-.775.65-1.287T10.5 2.5q.825 0 1.413.588T12.5 4.5t-.587 1.413M9.775 19h4.45l.575-6H9.2zM8 21l-.95-10h9.9L16 21z");
}

</style>
