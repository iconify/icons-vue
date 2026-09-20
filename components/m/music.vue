<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpljn4bnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:music" /></template>
<style>
.dpljn4bnh {
  fill: var(--svg-color--fbbf02, #fbbf02);
  d: path("M13.49 3.13A9 9 0 0 0 12 3.001a9 9 0 0 0-7.39 14.135c.618-.905 2.047-1.535 3.7-1.535c1.137 0 2.166.298 2.897.782zm4.782 2.425c1.558 3.436.191 5.276.191 5.276c-1.052-3.173-4.106-3.64-4.106-3.64s-2.02 10.829-2.02 10.97c0 1.169-1.242 2.159-2.935 2.457A9.004 9.004 0 0 0 21 12a8.96 8.96 0 0 0-2.728-6.445");
}

</style>
