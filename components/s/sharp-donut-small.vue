<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0mlr_b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-donut-small" /></template>
<style>
.u0mlr_b-m {
  fill: currentColor;
  d: path("M13 9.18c.85.3 1.51.97 1.82 1.82h7.13c-.47-4.72-4.23-8.48-8.95-8.95zm-2 5.64C9.84 14.4 9 13.3 9 12s.84-2.4 2-2.82V2.05c-5.05.5-9 4.76-9 9.95s3.95 9.45 9 9.95zM14.82 13c-.3.85-.97 1.51-1.82 1.82v7.13c4.72-.47 8.48-4.23 8.95-8.95z");
}

</style>
