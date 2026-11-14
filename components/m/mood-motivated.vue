<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ln3tedq8z"/><path class="mee2o7qts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-motivated" /></template>
<style>
.ln3tedq8z {
  d: path("M14.5 20.5q-.594.248-1.225.374T12 21q-.16 0-.319-.008t-.318-.023t-.317-.039t-.314-.055q-.157-.031-.311-.07q-.155-.039-.308-.085t-.303-.1t-.297-.115t-.292-.129t-.285-.144t-.278-.157t-.269-.17q-.133-.089-.261-.184t-.252-.196q-.123-.102-.241-.209t-.231-.22t-.22-.231t-.209-.241q-.101-.124-.196-.252t-.184-.261q-.088-.132-.17-.269t-.157-.278t-.144-.285q-.068-.144-.129-.292q-.061-.147-.115-.297t-.1-.303t-.085-.308t-.07-.311t-.055-.314q-.023-.158-.039-.317q-.015-.159-.023-.318T5.5 14.5c0-2.5.75-4.25 2-5.75c.5 2 1.5 3 2.5 3.5c0-3.75.75-6.75 2-9.75c3.227 2.868 5.168 5.737 6.008 8.605M18 21v-6");
}

.mee2o7qts {
  d: path("M15.5 17.5L18 15l2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
