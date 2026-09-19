<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcy9m98qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-bookmark-remove" /></template>
<style>
.rcy9m98qe {
  fill: currentColor;
  d: path("M17 11v6.97l-5-2.14l-5 2.14V5h6V3H7c-1.1 0-2 .9-2 2v16l7-3l7 3V11zm4-4h-6V5h6z");
}

</style>
