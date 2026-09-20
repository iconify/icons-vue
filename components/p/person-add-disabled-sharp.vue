<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsexaqbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-add-disabled-sharp" /></template>
<style>
.xsexaqbug {
  fill: currentColor;
  d: path("m19.166 21.523l-3.416-3.415v.507h-14V16.97q0-.619.36-1.159q.361-.539.97-.837q1.416-.679 2.834-1.018q1.417-.34 2.836-.34q.729 0 1.455.1t1.468.316l-2.665-2.665q-.05.019-.12.019H8.75q-1.237 0-2.119-.882T5.75 8.385v-.139q0-.069.02-.119L2.226 4.584l.714-.713L19.879 20.81zM18.25 13.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zm-6.746-3.915L7.55 5.63q.279-.123.583-.185q.304-.061.617-.061q1.238 0 2.119.88t.881 2.12q0 .313-.061.617q-.062.304-.185.582");
}

</style>
