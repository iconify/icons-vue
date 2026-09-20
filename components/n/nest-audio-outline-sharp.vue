<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abdj2-r-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-audio-outline-sharp" /></template>
<style>
.abdj2-r-x {
  fill: currentColor;
  d: path("M9.346 19.577q-1.3 0-2.227-.927t-.927-2.227V8.462q0-1.69 1.182-2.865q1.18-1.174 2.857-1.174h3.538q1.69 0 2.865 1.174q1.174 1.174 1.174 2.864v7.962q0 1.301-.927 2.228t-2.227.926zm0-1h5.308q.888 0 1.521-.633t.633-1.521V8.462q0-1.267-.886-2.153t-2.153-.886h-3.538q-1.266 0-2.152.886t-.887 2.152v7.962q0 .889.633 1.521t1.521.633m0-5.808q.31 0 .54-.23t.23-.539t-.23-.54t-.54-.23q-.31 0-.54.23q-.229.23-.229.54t.23.54t.54.23m2.653 0q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m2.654 0q.31 0 .54-.23q.229-.23.229-.54t-.23-.54t-.54-.23t-.538.23t-.23.54t.23.54t.539.23M12 12");
}

</style>
