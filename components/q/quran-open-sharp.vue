<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rc_f-5spx"/><path class="ylk10acha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quran-open-sharp" /></template>
<style>
.rc_f-5spx {
  d: path("M12 7C9.75 5.25 6.5 4.5 2.75 4.75v13.5c3.75-.25 7 .5 9.25 2.25c2.25-1.75 5.5-2.5 9.25-2.25V4.75c-3.75-.25-7 .5-9.25 2.25Zm0 0v13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ylk10acha {
  d: path("m5.25 9.5l1.5.75l1.5-.75c1-.5 2-.5 1 0m-4 3.5l1.5.75l1.5-.75l1.5-.75V13m6.99-3.34l.33.6l.14.26l.29-.08l.65-.19l.29-.09l-.09.29l-.19.65l-.08.29l.26.14l.6.33l.26.14l-.26.14l-.6.33l-.26.14l.08.29l.19.65l.09.29l-.29-.09l-.65-.19l-.29-.08l-.14.26l-.33.6l-.14.26l-.14-.26l-.33-.6l-.14-.26l-.29.08l-.65.19l-.29.09l.09-.29l.19-.65l.08-.29l-.26-.14l-.6-.33L14 12l.26-.14l.6-.33l.26-.14l-.08-.29l-.19-.65l-.09-.29l.29.09l.65.19l.29.08l.14-.26l.33-.6l.14-.26z");
}

</style>
