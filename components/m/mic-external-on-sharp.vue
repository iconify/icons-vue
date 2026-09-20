<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1o9cdb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mic-external-on-sharp" /></template>
<style>
.q1o9cdb-p {
  fill: currentColor;
  d: path("M5.416 7.462q-.26-.33-.396-.714q-.135-.385-.135-.787q0-1.038.73-1.769q.731-.73 1.77-.73q1.038 0 1.769.73t.73 1.77q0 .401-.135.786t-.395.713zm1.469 13.077V17.23h-.77l-.884-8.692h4.308l-.885 8.692h-.77v2.307H12.5V3.462h6.616v17.077h-1V4.462H13.5v16.077z");
}

</style>
