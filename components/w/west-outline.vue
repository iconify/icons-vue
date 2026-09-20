<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btc8qxb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:west-outline" /></template>
<style>
.btc8qxb5q {
  fill: currentColor;
  d: path("m9 19l-7-7l7-7l1.4 1.4L5.825 11H22v2H5.825l4.6 4.6z");
}

</style>
