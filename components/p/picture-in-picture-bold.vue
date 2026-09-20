<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="csbd4hb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:picture-in-picture-bold" /></template>
<style>
.csbd4hb8y {
  fill: currentColor;
  d: path("M216 44H40a20 20 0 0 0-20 20v128a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V64a20 20 0 0 0-20-20M44 68h168v48h-76a12 12 0 0 0-12 12v60H44Zm104 120v-48h64v48Z");
}

</style>
