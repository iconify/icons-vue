<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp9jj_b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-jam-sharp" /></template>
<style>
.vp9jj_b3a {
  fill: currentColor;
  d: path("M7 19.77v-1h5.5v-8.547l2.1 2.1l.708-.707L12 8.308l-3.308 3.308l.708.707l2.1-2.1V15H3V4h18v11h-7.5v3.77H17v1z");
}

</style>
