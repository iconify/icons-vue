<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bnozeq7dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-chat-16-regular" /></template>
<style>
.bnozeq7dm {
  fill: currentColor;
  d: path("m7.603 13.267l-.215.707C4.619 13.729 3 11.84 3 10v-.5A1.5 1.5 0 0 1 4.5 8h4.54c-.39.275-.733.613-1.012 1H4.5a.5.5 0 0 0-.5.5v.5c0 1.338 1.241 2.785 3.484 2.978q.054.147.119.29M8 1.5A2.75 2.75 0 1 1 8 7a2.75 2.75 0 0 1 0-5.5m0 1A1.75 1.75 0 1 0 8 6a1.75 1.75 0 0 0 0-3.5m7 9a3.5 3.5 0 0 1-5.197 3.062l-1.392.423a.318.318 0 0 1-.397-.397l.424-1.391A3.5 3.5 0 1 1 15 11.5M10.5 10a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm-.5 2.5a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 0-1h-1a.5.5 0 0 0-.5.5");
}

</style>
