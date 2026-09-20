<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qiujl4brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mic-off-20-filled" /></template>
<style>
.qiujl4brh {
  fill: currentColor;
  d: path("M13 10q0 .406-.102.777L7.002 4.881A3 3 0 0 1 13 5zM7 7.708V10a3 3 0 0 0 4.738 2.445l1.07 1.07A4.5 4.5 0 0 1 5.5 10a.5.5 0 0 0-.999.001a5.5 5.5 0 0 0 5 5.478V17.5a.5.5 0 0 0 1 0v-2.022a5.5 5.5 0 0 0 3.02-1.251l3.626 3.627a.5.5 0 0 0 .708-.707l-15-15a.5.5 0 1 0-.708.707zm7.803 4.975A5.5 5.5 0 0 0 15.5 10a.5.5 0 0 0-1 0c0 .695-.157 1.353-.439 1.94z");
}

</style>
