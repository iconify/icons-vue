<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ten5e80ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stack-off" /></template>
<style>
.ten5e80ko {
  fill: currentColor;
  d: path("M22 19.15L10.85 8H20q.825 0 1.413.588T22 10zM14 6V4H6.85l-2-2H14q.825 0 1.413.588T16 4v2zm6.575 17.425L19.15 22H10q-.85 0-1.425-.575T8 20v-9.15l-4-4V14h2v2H4q-.85 0-1.425-.575T2 14V4.85L.575 3.425L2 2l20 20z");
}

</style>
