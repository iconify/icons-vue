<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnfk03bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rtl-90-24-regular" /></template>
<style>
.bnfk03bpe {
  fill: currentColor;
  d: path("M8 6.25a.75.75 0 0 0-1.5 0v9a.75.75 0 0 0 1.5 0zm6.78 15.03a.75.75 0 0 0 .073-.976l-.073-.084l-2-2a.75.75 0 0 0-.976-.073l-.084.073l-2 2a.75.75 0 0 0 .976 1.133l.084-.073l1.47-1.47l1.47 1.47a.75.75 0 0 0 1.06 0M13 3.25a.75.75 0 0 0-1.5 0v12a.75.75 0 0 0 1.5 0zm5 3a.75.75 0 0 0-1.5 0v9a.75.75 0 0 0 1.5 0z");
}

</style>
