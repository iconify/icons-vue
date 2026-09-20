<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oilaccbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:variables" /></template>
<style>
.oilaccbua {
  fill: currentColor;
  d: path("M4 16V8h16v8z");
}

</style>
