<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cz3ey5bnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:midi-off-16-filled" /></template>
<style>
.cz3ey5bnd {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707L12.293 13H2.75A1.75 1.75 0 0 1 1 11.25v-6.5a1.75 1.75 0 0 1 1.342-1.701L1.146 1.854a.5.5 0 0 1 0-.707M13.25 3c.966 0 1.75.784 1.75 1.75v6.5c0 .452-.173.863-.455 1.174l-.71-.71A.74.74 0 0 0 14 11.25V8h-1v2.5a.5.5 0 0 1-.092.287L12 9.88V8h-1.879l-5-5zM2 11.25c0 .414.336.75.75.75h8.543l-1.326-1.326A.498.498 0 0 1 9 10.5v-.793L7.293 8H7v2.5a.5.5 0 1 1-1 0V8H4v2.5a.5.5 0 1 1-1 0V8H2zM3.5 5a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m7 0a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
}

</style>
