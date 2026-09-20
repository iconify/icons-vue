<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="idzy95hgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scales-28-regular" /></template>
<style>
.idzy95hgs {
  fill: currentColor;
  d: path("M24.25 3a.75.75 0 0 1 0 1.5h-1.72l3.41 7.954q.06.141.06.296a4.5 4.5 0 1 1-9 0q0-.155.06-.296L20.47 4.5h-5.72V20h5.75a2.5 2.5 0 0 1 0 5h-13a2.5 2.5 0 0 1 0-5h5.75V4.5H7.53l3.41 7.954q.06.141.06.296a4.5 4.5 0 1 1-9 0q0-.155.06-.296L5.47 4.5H3.75a.75.75 0 0 1 0-1.5zM7.5 21.5a1 1 0 1 0 0 2h13a1 1 0 1 0 0-2zm-3.902-8a2.999 2.999 0 0 0 5.804 0zm15 0a3 3 0 0 0 2.902 2.25a3 3 0 0 0 2.902-2.25zM3.888 12h5.224L6.5 5.904zm15 0h5.224L21.5 5.904z");
}

</style>
