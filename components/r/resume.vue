<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd2i9y3qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:resume" /></template>
<style>
.gd2i9y3qw {
  fill: currentColor;
  d: path("M6 18V6h2v12zm4 0l10-6l-10-6z");
}

</style>
