<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utmvh4blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:music-video" /></template>
<style>
.utmvh4blu {
  fill: currentColor;
  d: path("M12.275 16.275Q13 15.55 13 14.5V9h3V7h-4v5.5q-.325-.225-.7-.363T10.5 12q-1.05 0-1.775.725T8 14.5t.725 1.775T10.5 17t1.775-.725M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
