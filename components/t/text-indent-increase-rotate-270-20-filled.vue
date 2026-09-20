<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b4jhs0apv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-rotate-270-20-filled" /></template>
<style>
.b4jhs0apv {
  fill: currentColor;
  d: path("M10 2a.75.75 0 0 1 .75.75v9.5a.75.75 0 0 1-1.5 0v-9.5A.75.75 0 0 1 10 2M6.25 5.75a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0zm9 0a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0zm-4.28 12.03a.75.75 0 1 0 1.06-1.06l-1.5-1.5a.75.75 0 0 0-1.06 0l-1.5 1.5a.75.75 0 1 0 1.06 1.06l.97-.97z");
}

</style>
