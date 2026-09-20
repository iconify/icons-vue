<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uiilvacdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-right-add-20-filled" /></template>
<style>
.uiilvacdr {
  fill: currentColor;
  d: path("M18 6a2 2 0 0 0-2-2H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h5.207a5.5 5.5 0 0 1-.185-1H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h8v4.6c.75-.384 1.6-.6 2.5-.6c1.33 0 2.55.472 3.5 1.257zm-3.5 13a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a.5.5 0 0 1 .5.5V14h1.5a.5.5 0 0 1 0 1H15v1.5a.5.5 0 0 1-1 0V15h-1.5a.5.5 0 0 1 0-1H14v-1.5a.5.5 0 0 1 .5-.5");
}

</style>
