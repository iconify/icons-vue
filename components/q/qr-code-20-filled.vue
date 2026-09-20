<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5erdwbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:qr-code-20-filled" /></template>
<style>
.x5erdwbpk {
  fill: currentColor;
  d: path("M13 11h-2v2h2v2h-2v2h2v-2h2v2h2v-2h-2v-2h2v-2h-2v2h-2zM5 5h2v2H5zm0-2a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm-.75 1.75a.5.5 0 0 1 .5-.5h2.5a.5.5 0 0 1 .5.5v2.5a.5.5 0 0 1-.5.5h-2.5a.5.5 0 0 1-.5-.5zM5 13h2v2H5zm0-2a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2zm-.75 1.75a.5.5 0 0 1 .5-.5h2.5a.5.5 0 0 1 .5.5v2.5a.5.5 0 0 1-.5.5h-2.5a.5.5 0 0 1-.5-.5zM13 5h2v2h-2zm0-2a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm-.75 1.75a.5.5 0 0 1 .5-.5h2.5a.5.5 0 0 1 .5.5v2.5a.5.5 0 0 1-.5.5h-2.5a.5.5 0 0 1-.5-.5z");
}

</style>
