<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdu70j3ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-audio-sharp" /></template>
<style>
.mdu70j3ao {
  fill: currentColor;
  d: path("M9.346 19.577q-1.304 0-2.229-.925t-.925-2.229V8.462q0-1.69 1.184-2.865q1.184-1.174 2.855-1.174h3.538q1.69 0 2.865 1.174q1.174 1.174 1.174 2.864v7.962q0 1.304-.925 2.229t-2.23.925zm0-6.808q.31 0 .54-.23t.23-.539t-.23-.54t-.54-.23q-.31 0-.54.23q-.229.23-.229.54t.23.54t.54.23m2.653 0q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m2.654 0q.31 0 .54-.23q.229-.23.229-.54t-.23-.54t-.54-.23t-.538.23t-.23.54t.23.54t.539.23");
}

</style>
