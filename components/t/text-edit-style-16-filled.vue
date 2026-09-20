<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="walh_ybhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-edit-style-16-filled" /></template>
<style>
.walh_ybhk {
  fill: currentColor;
  d: path("M5.471 2.332a.5.5 0 0 0-.942 0l-2.5 7a.5.5 0 1 0 .942.336L3.924 7h2.152l.475 1.328l.782-.782zm-.47 1.655L5.718 6H4.281zm5.73 1.575a1.914 1.914 0 1 1 2.708 2.707l-4.657 4.657a2.5 2.5 0 0 1-1.278.683l-1.906.382a.5.5 0 0 1-.588-.589l.381-1.906a2.5 2.5 0 0 1 .684-1.277z");
}

</style>
