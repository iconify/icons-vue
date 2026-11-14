<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfltk-b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:share-2" /></template>
<style>
.yfltk-b9n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 5.5Q14 2 17.5 2T21 5.5T17.5 9q-1.865 0-2.736-.994l-4.878 2.845Q10 11.369 10 12t-.114 1.149l4.878 2.845Q15.635 15 17.5 15q3.5 0 3.5 3.5T17.5 22T14 18.5q0-.631.114-1.149l-4.878-2.845q-.871.994-2.736.994Q3 15.5 3 12t3.5-3.5q1.865 0 2.736.994l4.878-2.845Q14 6.131 14 5.5");
}

</style>
