<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osajfobgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:universal-currency-alt" /></template>
<style>
.osajfobgi {
  fill: currentColor;
  d: path("M15.308 15.692h3.384v-3.384h-.884v2.5h-2.5zM12 14.385q.98 0 1.683-.702q.702-.702.702-1.683t-.702-1.683T12 9.615t-1.683.702T9.615 12t.702 1.683t1.683.702m-6.692-2.693h.884v-2.5h2.5v-.884H5.308zM3 18V6h18v12z");
}

</style>
