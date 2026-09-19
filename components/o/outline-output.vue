<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_-fg2ogt"/><path class="b01xvhb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-output" /></template>
<style>
.b01xvhb1i {
  fill: currentColor;
  d: path("M19 19H5V5h14v2h2V5a2 2 0 0 0-2-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14a2 2 0 0 0 2-2v-2h-2z");
}

.r_-fg2ogt {
  fill: currentColor;
  d: path("m17 17l5-5l-5-5l-1.41 1.41L18.17 11H9v2h9.17l-2.58 2.59z");
}

</style>
