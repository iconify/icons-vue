<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-3klup6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sport-cricket-ball-20-filled" /></template>
<style>
.l-3klup6u {
  fill: currentColor;
  d: path("M10 2c1.515 0 2.932.422 4.14 1.153a.5.5 0 0 0-.14.348v1a.5.5 0 0 0 1 0v-.744A8 8 0 1 1 10 2M4.5 13.001a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 .999a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm0-3a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 1 0v-1a.5.5 0 0 0-.5-.5m2 1a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z");
}

</style>
