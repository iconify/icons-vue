<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="op5tlpb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scales-28-filled" /></template>
<style>
.op5tlpb7s {
  fill: currentColor;
  d: path("M24.25 3a.75.75 0 0 1 0 1.5h-1.72l3.41 7.954q.06.141.06.296a4.5 4.5 0 1 1-9 0q0-.155.06-.296L20.47 4.5h-5.72V20h5.75a2.5 2.5 0 0 1 0 5h-13a2.5 2.5 0 0 1 0-5h5.75V4.5H7.53l3.41 7.954q.06.141.06.296a4.5 4.5 0 1 1-9 0q0-.155.06-.296L5.47 4.5H3.75a.75.75 0 0 1 0-1.5zM3.888 12h5.224L6.5 5.904zm15 0h5.224L21.5 5.904z");
}

</style>
