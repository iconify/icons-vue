<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9m2ldb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-divide" /></template>
<style>
.j9m2ldb1e {
  fill: currentColor;
  d: path("M5 11h14v2H5zm7.002-7a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4m0 12a2 2 0 1 0-.004 4a2 2 0 0 0 .004-4");
}

</style>
