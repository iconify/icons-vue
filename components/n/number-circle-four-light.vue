<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nb3ld6f6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-circle-four-light" /></template>
<style>
.nb3ld6f6i {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m32-72h-10V80a6 6 0 0 0-10.74-3.68l-56 72A6 6 0 0 0 88 158h50v18a6 6 0 0 0 12 0v-18h10a6 6 0 0 0 0-12m-22 0h-37.73L138 97.49Z");
}

</style>
