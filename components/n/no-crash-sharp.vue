<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg3600btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:no-crash-sharp" /></template>
<style>
.bg3600btt {
  fill: currentColor;
  d: path("m12 6.35l-2.825-2.8l1.4-1.425L12 3.55L15.55 0l1.4 1.4zM3 24v-9l2.45-7h13.1L21 15v9h-3v-2H6v2zm2.8-11h12.4l-1.05-3H6.85zm1.7 6q.625 0 1.063-.437T9 17.5t-.437-1.062T7.5 16t-1.062.438T6 17.5t.438 1.063T7.5 19m9 0q.625 0 1.063-.437T18 17.5t-.437-1.062T16.5 16t-1.062.438T15 17.5t.438 1.063T16.5 19");
}

</style>
