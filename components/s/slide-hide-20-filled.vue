<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nii0wx1tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-hide-20-filled" /></template>
<style>
.nii0wx1tq {
  fill: currentColor;
  d: path("M6 3a4 4 0 0 0-4 4v5a2 2 0 0 0 2 2V8a3 3 0 0 1 3-3h8a2 2 0 0 0-2-2zm0 5a1 1 0 0 1 1-1h.5a.5.5 0 0 0 0-1H7a2 2 0 0 0-2 2v.5a.5.5 0 0 0 1 0zm3.5-2a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm3 0a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm3 0a.5.5 0 0 0 0 1h.5a1 1 0 0 1 1 1v.5a.5.5 0 0 0 1 0V8a2 2 0 0 0-2-2zM6 10.5a.5.5 0 0 0-1 0v2a.5.5 0 0 0 1 0zm12 0a.5.5 0 0 0-1 0v2a.5.5 0 0 0 1 0zm-12 4a.5.5 0 0 0-1 0v.5a2 2 0 0 0 2 2h.5a.5.5 0 0 0 0-1H7a1 1 0 0 1-1-1zm12 0a.5.5 0 0 0-1 0v.5a1 1 0 0 1-1 1h-.5a.5.5 0 0 0 0 1h.5a2 2 0 0 0 2-2zM9.5 16a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm3 0a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z");
}

</style>
