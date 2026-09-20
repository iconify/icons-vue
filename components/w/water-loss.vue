<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl7__vbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:water-loss" /></template>
<style>
.fl7__vbrm {
  fill: currentColor;
  d: path("M6.412 15.539q1.125-.52 2.29-.78q1.165-.259 2.385-.259q.73 0 1.458.09t1.434.29q1.327.37 2.018.495q.692.125 1.5.125h.091L18.866 4H5.116zM7.475 21q-.64 0-1.097-.404t-.513-1.025L4 3h16l-1.846 16.571q-.056.621-.513 1.025q-.456.404-1.097.404z");
}

</style>
