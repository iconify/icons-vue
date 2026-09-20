<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wnt-_qivg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:play-28-regular" /></template>
<style>
.wnt-_qivg {
  fill: currentColor;
  d: path("M9.38 4.677a1.25 1.25 0 0 0-1.88 1.08v16.488a1.25 1.25 0 0 0 1.88 1.079l14.698-8.59a.85.85 0 0 0 0-1.467zM6 5.757c0-2.124 2.304-3.447 4.138-2.375l14.697 8.59c1.552.907 1.552 3.15 0 4.057l-14.697 8.59C8.304 25.691 6 24.369 6 22.245z");
}

</style>
