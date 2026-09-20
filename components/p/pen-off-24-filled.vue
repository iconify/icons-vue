<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lku_1ve4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pen-off-24-filled" /></template>
<style>
.lku_1ve4y {
  fill: currentColor;
  d: path("m14 15.06l6.72 6.72a.75.75 0 0 0 1.06-1.06L3.28 2.22a.75.75 0 0 0-1.06 1.06L8.94 10l-5 4.999a3.1 3.1 0 0 0-.825 1.476L2.02 21.077a.75.75 0 0 0 .904.903l4.601-1.096a3.1 3.1 0 0 0 1.477-.825zm4.995-2.53l-1.642 1.642l1.061 1.06l1.642-1.641a3.25 3.25 0 0 0 .005-4.592l.891-.891a3.578 3.578 0 0 0-5.06-5.06l-4.832 4.83l5.061 5.061L19 10.06a1.75 1.75 0 0 1-.005 2.471");
}

</style>
