<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmu6bib1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:person-raised-hand" /></template>
<style>
.jmu6bib1k {
  fill: currentColor;
  d: path("M3 21.23v-1h18v1zM5 19v-4.692q-.863-1.716-1.304-3.305q-.44-1.59-.44-3.01q0-1.18.3-2.453q.302-1.273.923-2.948q.084-.256.284-.424T5.244 2q.333 0 .556.266q.223.265.18.605l-.255 2.064q-.15 1.315.318 2.582T7.4 9.78t2.087 1.608T12 12q1.558 0 2.83.216q1.272.217 2.166.638q.952.46 1.478 1.184T19 15.85V19H9.539v-.406q0-.985.69-1.674q.69-.69 1.694-.69h3.385v-1h-3.385q-1.406 0-2.395.98q-.99.978-.99 2.384V19zm4.877-9.339Q9 8.785 9 7.54q0-1.247.877-2.124q.877-.876 2.123-.876t2.123.876T15 7.54t-.877 2.123t-2.123.876t-2.123-.876");
}

</style>
