<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fateippjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:minimize-outline-rounded" /></template>
<style>
.fateippjw {
  fill: currentColor;
  d: path("M7 20q-.213 0-.356-.144t-.144-.357t.144-.356T7 19h10q.213 0 .356.144t.144.357t-.144.356T17 20z");
}

</style>
