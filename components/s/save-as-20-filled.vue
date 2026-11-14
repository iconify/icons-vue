<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q2_dgobjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-as-20-filled" /></template>
<style>
.q2_dgobjw {
  fill: currentColor;
  d: path("M15.81 10.548a1.87 1.87 0 1 1 2.644 2.644l-4.829 4.83a2.2 2.2 0 0 1-1.021.578l-1.498.375a.89.89 0 0 1-1.079-1.08l.374-1.497c.097-.387.297-.74.579-1.021zM6 6.5A1.5 1.5 0 0 0 7.5 8h4A1.5 1.5 0 0 0 13 6.5V3h.379a2 2 0 0 1 1.414.586l1.621 1.621A2 2 0 0 1 17 6.621v2.385c-.69.032-1.37.308-1.898.835l-.572.571A1.5 1.5 0 0 0 13.5 10h-7A1.5 1.5 0 0 0 5 11.5V17a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h1zm7.5 4.5c.123 0 .235.046.322.12l-3.549 3.55c-.41.41-.7.923-.84 1.485L9.222 17H6v-5.5a.5.5 0 0 1 .5-.5zM12 6.5a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5V3h5z");
}

</style>
