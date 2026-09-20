<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u2owf4r3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:street-sign-20-filled" /></template>
<style>
.u2owf4r3k {
  fill: currentColor;
  d: path("M7 4a2 2 0 1 1 4 0v1h2.379a2 2 0 0 1 1.414.586l2.06 2.06a.5.5 0 0 1 0 .708l-2.06 2.06a2 2 0 0 1-1.414.586H11v6a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-6H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h2zm3 0a1 1 0 0 0-2 0v1h2zM8 17h2v-6H8z");
}

</style>
