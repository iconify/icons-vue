<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qsmx-dh8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-car-profile-ltr-clock-20-filled" /></template>
<style>
.qsmx-dh8p {
  fill: currentColor;
  d: path("M10 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M5.5 3a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5H7a.5.5 0 0 0 0-1H6V3.5a.5.5 0 0 0-.5-.5M3 12.562c0-.713.302-1.37.797-1.83A5.5 5.5 0 0 0 5.5 11c1.86 0 3.505-.923 4.5-2.337V10h3.873l-1.239-2.228A1.5 1.5 0 0 0 11.324 7h-.531q.137-.484.185-1h.345a2.5 2.5 0 0 1 2.186 1.286l1.542 2.777l2.093.558A2.5 2.5 0 0 1 19 13.037v1.213a1.75 1.75 0 0 1-1.023 1.592A2.5 2.5 0 0 1 13.05 16h-4.1a2.5 2.5 0 0 1-4.927-.158A1.75 1.75 0 0 1 3 14.25zM5 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0m9 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0");
}

</style>
