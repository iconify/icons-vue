<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4aosrjtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-duplicate" /></template>
<style>
.y4aosrjtt {
  fill: currentColor;
  d: path("M8 18q-.825 0-1.412-.587T6 16V4q0-.825.588-1.412T8 2h12q.825 0 1.413.588T22 4v12q0 .825-.587 1.413T20 18zm-2 4v-2h2v2zM4 6H2q0-.825.588-1.412T4 4zm6 16v-2h2v2zm4 0v-2h2v2zM4 20v2q-.825 0-1.412-.587T2 20zm-2-2v-2h2v2zm0-4v-2h2v2zm0-4V8h2v2zm16 10h2q0 .825-.587 1.413T18 22zM13 8h7V4h-7z");
}

</style>
