<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aktvng8pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nightlight-sharp" /></template>
<style>
.aktvng8pn {
  fill: currentColor;
  d: path("M14.5 21q-1.858 0-3.5-.71q-1.642-.711-2.86-1.93T6.21 15.5t-.71-3.503t.71-3.5T8.14 5.64T11 3.71Q12.642 3 14.5 3q.812 0 1.558.139q.746.138 1.442.442q-1.833 1.498-2.916 3.674Q13.5 9.43 13.5 12t1.084 4.745T17.5 20.42q-.696.304-1.442.443Q15.312 21 14.5 21");
}

</style>
