<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4v8ybrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-person-pin" /></template>
<style>
.ul4v8ybrz {
  fill: currentColor;
  d: path("M21 2H3v18h6l3 3l3-3h6zm-9 3.3c1.49 0 2.7 1.21 2.7 2.7s-1.21 2.7-2.7 2.7S9.3 9.49 9.3 8s1.21-2.7 2.7-2.7M18 16H6v-.9c0-2 4-3.1 6-3.1s6 1.1 6 3.1z");
}

</style>
