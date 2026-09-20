<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_03v87lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:step" /></template>
<style>
.i_03v87lv {
  fill: currentColor;
  d: path("M18.692 14.904q-1.063 0-1.791-.738q-.728-.737-.728-1.8t.728-1.802t1.791-.737q1.045 0 1.782.737t.738 1.801t-.738 1.801t-1.782.738m-9.365 1.808l-.708-.695l3.094-3.151H2.77v-1h8.964L8.619 8.727L9.327 8l4.327 4.366z");
}

</style>
