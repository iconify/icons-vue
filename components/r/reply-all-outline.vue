<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilpl2-b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:reply-all-outline" /></template>
<style>
.ilpl2-b3l {
  fill: currentColor;
  d: path("m8 17l-6-6l6-6l1.425 1.4l-4.6 4.6l4.6 4.6zm12 2v-4q0-1.25-.875-2.125T17 12h-6.175l3.6 3.6L13 17l-6-6l6-6l1.425 1.4l-3.6 3.6H17q2.075 0 3.538 1.463T22 15v4z");
}

</style>
