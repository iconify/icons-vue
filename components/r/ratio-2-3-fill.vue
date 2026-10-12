<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlt9ap3kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ratio-2-3-fill" /></template>
<style>
.rlt9ap3kn {
  fill: currentColor;
  d: path("M4 5C4 2.7909 5.7909 1 8 1L16 1C18.2091 1 20 2.7909 20 5L20 19C20 21.2091 18.2091 23 16 23L8 23C5.7909 23 4 21.2091 4 19L4 5Z");
}

</style>
