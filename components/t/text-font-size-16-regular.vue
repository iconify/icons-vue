<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mekel5b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-16-regular" /></template>
<style>
.mekel5b4q {
  fill: currentColor;
  d: path("M10.5 2a.5.5 0 0 1 .47.33l4 11a.5.5 0 1 1-.94.34L12.695 10h-4.39l-1.336 3.67a.5.5 0 0 1-.931.022L5.333 12H2.667l-.706 1.692a.5.5 0 0 1-.923-.384l2.5-6a.501.501 0 0 1 .924 0l2.005 4.815L10.03 2.33l.032-.071A.5.5 0 0 1 10.5 2m-7.416 9h1.832L4 8.8zm5.584-2h3.664L10.5 3.962z");
}

</style>
