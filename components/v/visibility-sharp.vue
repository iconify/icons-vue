<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea69meavv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:visibility-sharp" /></template>
<style>
.ea69meavv {
  fill: currentColor;
  d: path("M14.591 14.087q1.063-1.067 1.063-2.591t-1.067-2.587t-2.591-1.063t-2.587 1.067t-1.063 2.592t1.067 2.586t2.592 1.063t2.586-1.067m-4.503-.674Q9.3 12.625 9.3 11.5t.788-1.912T12 8.8t1.913.788t.787 1.912t-.787 1.913T12 14.2t-1.912-.787M6.08 16.232Q3.408 14.464 2.077 11.5q1.33-2.964 4.001-4.732T11.998 5t5.921 1.768t4.004 4.732q-1.33 2.964-4.001 4.732T12.002 18t-5.921-1.768");
}

</style>
