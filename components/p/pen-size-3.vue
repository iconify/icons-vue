<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9rq_641f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pen-size-3" /></template>
<style>
.s9rq_641f {
  fill: currentColor;
  d: path("M5.796 18.204q-.29-.29-.29-.704t.29-.704l11.02-11q.29-.296.694-.293t.694.293t.293.704t-.293.704l-11 11q-.29.29-.704.293t-.704-.293");
}

</style>
