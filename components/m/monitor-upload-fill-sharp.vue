<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne84dfbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-upload-fill-sharp" /></template>
<style>
.ne84dfbza {
  fill: currentColor;
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm8.293 2.293l-3 3a.999.999 0 1 0 1.414 1.414L11 9.414V14a1 1 0 0 0 2 0V9.414l1.293 1.293a.999.999 0 1 0 1.414-1.414l-3-3a1 1 0 0 0-1.414 0M9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
