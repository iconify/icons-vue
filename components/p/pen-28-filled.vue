<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n4iv_bcdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pen-28-filled" /></template>
<style>
.n4iv_bcdz {
  fill: currentColor;
  d: path("M19.289 3.15a3.932 3.932 0 1 1 5.56 5.56l-1.54 1.54a3.25 3.25 0 0 1-.046 4.548L21.28 16.78a.75.75 0 1 1-1.06-1.06l1.982-1.983a1.75 1.75 0 0 0 .047-2.426L10.063 23.497c-.44.44-.987.76-1.587.928l-5.524 1.547a.75.75 0 0 1-.924-.924l1.547-5.525c.168-.6.487-1.146.928-1.586z");
}

</style>
