<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rlkns080e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:skip-back-15-20-filled" /></template>
<style>
.rlkns080e {
  fill: currentColor;
  d: path("M3.25 3a.75.75 0 0 1 .75.75v1.839A8.23 8.23 0 0 1 10 3a8.24 8.24 0 0 1 6.977 3.845a.75.75 0 1 1-1.267.802A6.75 6.75 0 0 0 10 4.5a6.73 6.73 0 0 0-4.795 2H7.25a.75.75 0 0 1 0 1.5h-4a.75.75 0 0 1-.75-.75v-3.5A.75.75 0 0 1 3.25 3m11.25 7.75a.75.75 0 0 1-.75.75h-1.84l-.062.503h.52a2.5 2.5 0 1 1-2.132 3.562a.75.75 0 1 1 1.357-.64q.078.165.208.292a1 1 0 1 0 .634-1.715l-.046.001H11a.75.75 0 0 1-.744-.842l.248-2.003a.75.75 0 0 1 .744-.658h2.501a.75.75 0 0 1 .75.75m-6.933-.681a.75.75 0 0 1 .437.681v5.5a.75.75 0 0 1-1.5 0v-3.868l-.516.442a.75.75 0 0 1-.976-1.138l1.754-1.505a.75.75 0 0 1 .801-.112");
}

</style>
