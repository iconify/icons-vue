<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e76uccbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mode-comment-outline-sharp" /></template>
<style>
.e76uccbpf {
  fill: currentColor;
  d: path("M3 17V3h18v17.077L17.923 17zm1-1h14.35L20 17.644V4H4zm0 0V4z");
}

</style>
