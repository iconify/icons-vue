<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em0bhin0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-hand" /></template>
<style>
.em0bhin0t {
  fill: currentColor;
  d: path("M6.616 21q-.672 0-1.144-.472T5 19.385V4.615q0-.67.472-1.143Q5.944 3 6.616 3h7.846q.67 0 1.143.472q.472.472.472 1.144v.519h-2.616v7.602l-1.25-.631q-.988-.495-2.057-.287t-1.838.996l-1.65 1.714L11.785 21zm9.161 0q-.43 0-.814-.159q-.384-.158-.66-.508l-4.476-5.64l.221-.222q.218-.217.515-.29q.296-.071.595.071l4.688 2.306V7.519h.923q1.25 0 2.125.875t.875 2.125V18q0 1.25-.875 2.125T16.77 21zM11.078 7.078q.23-.23.23-.54T11.078 6t-.54-.23T10 6t-.23.54q0 .309.23.539t.54.23t.539-.23");
}

</style>
