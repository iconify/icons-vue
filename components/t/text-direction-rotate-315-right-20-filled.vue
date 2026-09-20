<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vee4d2bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-315-right-20-filled" /></template>
<style>
.vee4d2bko {
  fill: currentColor;
  d: path("M8 2.75A.75.75 0 0 1 8.75 2h2.5a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-1.5 0v-.69L8.28 6.78a.75.75 0 1 1-1.06-1.06L9.44 3.5h-.69A.75.75 0 0 1 8 2.75M3.084 6.58A.75.75 0 0 0 2.08 7.584l4 8a.75.75 0 0 0 1.342-.671L6.33 12.73l1.901-1.902l2.184 1.092a.75.75 0 1 0 .67-1.341zm3.732 3.542l-1.195 1.195l-1.195-2.39zM14.75 8a.75.75 0 0 0 0 1.5h.69l-7.22 7.22a.75.75 0 1 0 1.061 1.06l7.22-7.22v.69a.75.75 0 0 0 1.5 0v-2.5a.75.75 0 0 0-.75-.75z");
}

</style>
