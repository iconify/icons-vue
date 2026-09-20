<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5yjo2x3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-access-3-outline-sharp" /></template>
<style>
.e5yjo2x3e {
  fill: currentColor;
  d: path("M10.596 21v-3h1v1.385q0 .269.173.442t.443.173h7.173q.269 0 .442-.173t.173-.443V4h-8.404v2h-1V3H21v4.817h.962v3.654H21V21zM3 17.77v-2.885h2.904v2.884zm7.077-2.616l-.688-.708l1.94-1.946H3v-1h8.329l-1.94-1.946l.688-.708L13.231 12zM3 9.116V6.212h2.904v2.904z");
}

</style>
