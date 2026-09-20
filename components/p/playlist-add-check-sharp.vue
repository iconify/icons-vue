<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1pk5zb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:playlist-add-check-sharp" /></template>
<style>
.t1pk5zb5q {
  fill: currentColor;
  d: path("M3.5 15.5v-1h7v1zm0-4v-1h11v1zm0-4v-1h11v1zm12.85 10.808l-2.858-2.858l.708-.708l2.15 2.139l4.25-4.25l.708.719z");
}

</style>
