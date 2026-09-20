<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjk5cze9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smart-card-reader-sharp" /></template>
<style>
.cjk5cze9x {
  fill: currentColor;
  d: path("M2 22v-5h20v5zm3-6.5V2h14v13.5zM8 14h.575q1.1 0 1.763-1.1T11 10t-.663-2.9T8.576 6H8zm6-2q.825 0 1.413-.587T16 10t-.587-1.412T14 8t-1.412.588T12 10t.588 1.413T14 12");
}

</style>
