<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq1o3xtmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phonelink-off-sharp" /></template>
<style>
.mq1o3xtmm {
  fill: currentColor;
  d: path("m8.85 6l-2-2H21v2zM22 19l-8-7.85V8h8zm-2.2 3.6L17.2 20H14v-3.2l-8-8V17h6v3H2v-3h2V6.8L1.4 4.2l1.4-1.4l18.4 18.4z");
}

</style>
