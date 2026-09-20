<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yi3j8pbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-circle-six-fill" /></template>
<style>
.yi3j8pbex {
  fill: currentColor;
  d: path("M148 148a20 20 0 1 1-20-20a20 20 0 0 1 20 20m84-20A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104m-68 20a36 36 0 0 0-36-36h-1.82l16.69-27.9a8 8 0 0 0-13.74-8.2s-32.4 54.28-32.47 54.42A36 36 0 1 0 164 148");
}

</style>
