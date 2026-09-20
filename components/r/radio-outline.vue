<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-3cembna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:radio-outline" /></template>
<style>
.b-3cembna {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20V8q0-.625.338-1.125t.912-.725L15.9 1l.65 1.65L8.3 6H20q.825 0 1.413.588T22 8v12q0 .825-.587 1.413T20 22zm0-2h16v-7H4zm5.775-1.725q.725-.725.725-1.775t-.725-1.775T8 14t-1.775.725T5.5 16.5t.725 1.775T8 19t1.775-.725M4 11h12V9h2v2h2V8H4zm0 9v-7z");
}

</style>
