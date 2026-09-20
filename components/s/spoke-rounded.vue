<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szd19nb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:spoke-rounded" /></template>
<style>
.szd19nb9k {
  fill: currentColor;
  d: path("M12 11q-1.65 0-2.825-1.175T8 7t1.175-2.825T12 3t2.825 1.175T16 7t-1.175 2.825T12 11M7 21q-1.65 0-2.825-1.175T3 17t1.175-2.825T7 13t2.825 1.175T11 17t-1.175 2.825T7 21m10 0q-1.65 0-2.825-1.175T13 17t1.175-2.825T17 13t2.825 1.175T21 17t-1.175 2.825T17 21");
}

</style>
