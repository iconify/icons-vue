<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj5p9mb7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:restore-page-sharp" /></template>
<style>
.hj5p9mb7y {
  fill: currentColor;
  d: path("M12 17.135q1.72 0 2.927-1.208T16.135 13t-1.208-2.927T12 8.866q-1.065 0-1.852.465t-1.321 1.065V8.692h-.885v3.25h3.25v-.884H9.431q.386-.547 1.063-.927T12 9.75q1.35 0 2.3.95t.95 2.3t-.95 2.3t-2.3.95q-1.1 0-1.925-.638T8.9 14h-.935q.408 1.452 1.513 2.293t2.522.842M5 21V3h8.577L19 8.423V21z");
}

</style>
