<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us9mvwbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:style-guide-24-filled" /></template>
<style>
.us9mvwbxn {
  fill: currentColor;
  d: path("m17.402 4.723l2.718 10.142a2.75 2.75 0 0 1-1.945 3.368l-6.278 1.682a2.75 2.75 0 0 1-3.368-1.944L5.81 7.828A2.75 2.75 0 0 1 7.756 4.46l6.278-1.682a2.75 2.75 0 0 1 3.368 1.945m-6.438 3.019a1 1 0 1 0-1.932.517a1 1 0 0 0 1.932-.517m-5.163 3.917l1.762 6.57a3.73 3.73 0 0 0 1.002 1.713l-.443-.023a2.75 2.75 0 0 1-2.602-2.89zm-.925-1.479l-.355 6.796c-.037.699.12 1.363.424 1.94l-.414-.16a2.75 2.75 0 0 1-1.582-3.553z");
}

</style>
