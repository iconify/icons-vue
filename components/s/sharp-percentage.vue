<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1gbu0bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-percentage" /></template>
<style>
.u1gbu0bhk {
  fill: currentColor;
  d: path("m18.501 3.5l-15 15.001l1.996 1.996l15-15zM7.002 5a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4m10 10a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4");
}

</style>
