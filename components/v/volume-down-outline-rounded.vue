<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls0mqbb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:volume-down-outline-rounded" /></template>
<style>
.ls0mqbb5e {
  fill: currentColor;
  d: path("M9.423 14H6.808q-.348 0-.578-.23T6 13.192v-2.384q0-.348.23-.578t.578-.23h2.615l2.685-2.685q.244-.244.568-.116t.324.476v8.65q0 .348-.324.476t-.568-.116zm8.077-2q0 .82-.302 1.555q-.302.736-.846 1.278q-.173.13-.378.041t-.205-.312V9.389q0-.223.205-.313t.378.041q.544.548.846 1.306T17.5 12M12 8.85L9.85 11H7v2h2.85L12 15.15zM9.5 12");
}

</style>
