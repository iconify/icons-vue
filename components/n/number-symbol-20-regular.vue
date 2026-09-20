<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k9qteq2yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-symbol-20-regular" /></template>
<style>
.k9qteq2yd {
  fill: currentColor;
  d: path("M8.99 2.598a.5.5 0 0 0-.98-.196l-.92 4.602H3.5a.5.5 0 1 0 0 1h3.39l-.8 3.993H2.5a.5.5 0 0 0 0 1h3.39l-.88 4.405a.5.5 0 1 0 .98.196l.92-4.601h5.004L11.01 17.4a.5.5 0 0 0 .98.2l.945-4.603h3.568a.5.5 0 0 0 0-1H13.14l.82-3.992h3.54a.5.5 0 1 0 0-1h-3.334l.901-4.391a.5.5 0 1 0-.98-.201l-.942 4.591H8.109zM7.91 8.004h5.03l-.82 3.993H7.11z");
}

</style>
