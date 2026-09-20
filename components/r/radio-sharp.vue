<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0dehmwic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:radio-sharp" /></template>
<style>
.q0dehmwic {
  fill: currentColor;
  d: path("M2 22V6.65L15.9 1l.65 1.65L8.3 6H22v16zm7.775-3.725q.725-.725.725-1.775t-.725-1.775T8 14t-1.775.725T5.5 16.5t.725 1.775T8 19t1.775-.725M4 11h12V9h2v2h2V8H4z");
}

</style>
