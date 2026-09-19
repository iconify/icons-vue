<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb7y69bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-minimize" /></template>
<style>
.vb7y69bfo {
  fill: currentColor;
  d: path("M6 19h12v2H6z");
}

</style>
