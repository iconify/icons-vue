<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bsmalc28k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-32-light" /></template>
<style>
.bsmalc28k {
  fill: currentColor;
  d: path("M13.5 24a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1zM10.25 2A3.25 3.25 0 0 0 7 5.25v21.5A3.25 3.25 0 0 0 10.25 30h11.5A3.25 3.25 0 0 0 25 26.75V5.25A3.25 3.25 0 0 0 21.75 2zM8 5.25A2.25 2.25 0 0 1 10.25 3h11.5A2.25 2.25 0 0 1 24 5.25v21.5A2.25 2.25 0 0 1 21.75 29h-11.5A2.25 2.25 0 0 1 8 26.75z");
}

</style>
