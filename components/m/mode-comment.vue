<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm_rjp-7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mode-comment" /></template>
<style>
.rm_rjp-7f {
  fill: currentColor;
  d: path("M4.616 17q-.691 0-1.153-.462T3 15.385V4.615q0-.69.463-1.153T4.615 3h14.77q.69 0 1.152.462T21 4.615v15.462L17.923 17z");
}

</style>
