<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t8fp2vnvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-list-28-filled" /></template>
<style>
.t8fp2vnvo {
  fill: currentColor;
  d: path("M9.5 14a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m14-3.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0M2 18.25A2.25 2.25 0 0 1 4.25 16h10.5q.355.001.678.104a1.75 1.75 0 0 0 .42 2.646a1.75 1.75 0 0 0-.052 2.967a5 5 0 0 1-.178.199a2 2 0 0 0-.206.205C14.337 23.143 12.53 24 9.5 24C2 24 2 18.75 2 18.75zm14.75-1.75a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
