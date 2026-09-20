<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n8wc_kb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-link-28-filled" /></template>
<style>
.n8wc_kb1v {
  fill: currentColor;
  d: path("M18.25 18.5a.75.75 0 0 1 0 1.5h-.5a2.25 2.25 0 0 0 0 4.5h.5a.75.75 0 0 1 0 1.5h-.5a3.75 3.75 0 1 1 0-7.5zm5 0a3.75 3.75 0 1 1 0 7.5h-.5a.75.75 0 0 1 0-1.5h.5a2.25 2.25 0 0 0 0-4.5h-.5a.75.75 0 0 1 0-1.5zM22.247 4a3.75 3.75 0 0 1 3.75 3.75V11H26v7.378a4.73 4.73 0 0 0-2.75-.878h-5.5a4.75 4.75 0 0 0-4.416 6.5H5.75A3.75 3.75 0 0 1 2 20.25V7.75A3.75 3.75 0 0 1 5.75 4zm1.003 17.5a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5z");
}

</style>
