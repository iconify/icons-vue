<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcxcmr9zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:primrose" /></template>
<style>
.jcxcmr9zf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.55 5.971q-1.514-.447-3.354.665q-3.382 2.043-1.59 5.565q.873 1.715 2.185 2.232q-.829 1.239-.441 3.275q.767 4.032 4.823 3.405q1.925-.297 2.827-1.371q.902 1.074 2.827 1.371q4.056.627 4.823-3.405q.388-2.036-.441-3.275q1.312-.517 2.185-2.232q1.792-3.522-1.59-5.565q-1.84-1.112-3.354-.665q-.005-1.565-1.566-3.008q-2.884-2.665-5.768 0Q7.555 4.406 7.55 5.971M9.5 12q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 12t-.732 1.768T12 14.5q-2.5 0-2.5-2.5");
}

</style>
