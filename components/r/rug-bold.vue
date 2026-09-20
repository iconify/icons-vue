<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ftfht4bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rug-bold" /></template>
<style>
.ftfht4bzx {
  fill: currentColor;
  d: path("M200 12a12 12 0 0 0-12 12v12h-24V24a12 12 0 0 0-24 0v12h-24V24a12 12 0 0 0-24 0v12H68V24a12 12 0 0 0-24 0v208a12 12 0 0 0 24 0v-12h24v12a12 12 0 0 0 24 0v-12h24v12a12 12 0 0 0 24 0v-12h24v12a12 12 0 0 0 24 0V24a12 12 0 0 0-12-12M68 60h120v136H68Zm60 120a12 12 0 0 0 10.29-5.83l24-40a12 12 0 0 0 0-12.34l-24-40a12 12 0 0 0-20.58 0l-24 40a12 12 0 0 0 0 12.34l24 40A12 12 0 0 0 128 180m0-68.68L138 128l-10 16.68L118 128Z");
}

</style>
