<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl0c5zubr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-fill" /></template>
<style>
.rl0c5zubr {
  fill: currentColor;
  d: path("M15.382 18H8.618l-1.724 3.447a1 1 0 1 1-1.788-.894l1.305-2.611A3 3 0 0 1 4 15V7c0-1.039.578-1.992 1.293-2.707l1-1C7.008 2.578 7.961 2 9 2h6c1.039 0 1.992.578 2.707 1.293l1 1C19.422 5.008 20 5.961 20 7v8a3 3 0 0 1-2.411 2.942l1.305 2.611a1 1 0 1 1-1.788.894ZM6 6.828V9h12V6.828a1 1 0 0 0-.293-.707l-1.828-1.828A1 1 0 0 0 15.172 4H8.828a1 1 0 0 0-.707.293L6.293 6.121A1 1 0 0 0 6 6.828M9.01 13H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m6 0H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
