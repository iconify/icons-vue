<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r3zqwvlbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-topic-add-16-filled" /></template>
<style>
.r3zqwvlbt {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2a.5.5 0 0 0-.5.5V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12V9.5a.5.5 0 0 0-.5-.5m0-3a5.49 5.49 0 0 0-4.242 2H3.5a.5.5 0 0 0 0 1h3.102a5.5 5.5 0 0 0-.394 1H3.5a.5.5 0 0 0 0 1h2.523a5.5 5.5 0 0 0 .578 3H3.5a2.5 2.5 0 0 1-2.487-2.244L1 11.5v-3A2.5 2.5 0 0 1 3.5 6zm2-4a1.5 1.5 0 0 1 0 3h-11a1.5 1.5 0 1 1 0-3z");
}

</style>
