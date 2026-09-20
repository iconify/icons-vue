<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvo56cspz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-multiple-off-16-regular" /></template>
<style>
.fvo56cspz {
  fill: currentColor;
  d: path("M1.147 1.147a.5.5 0 0 1 .707 0l13 13a.5.5 0 0 1-.707.707l-1.696-1.696A3.98 3.98 0 0 1 10 14H6.5a2.5 2.5 0 0 1-2-1H10a3 3 0 0 0 1.735-.558l-.857-.857A2.5 2.5 0 0 1 9.5 12h-5A2.5 2.5 0 0 1 2 9.5v-5c0-.51.152-.984.414-1.379L1.147 1.854a.5.5 0 0 1 0-.707M13 4.5c.607.456 1 1.182 1 2V10c0 .554-.114 1.082-.317 1.562l-.787-.788c.065-.247.104-.506.104-.774zm-10 5A1.5 1.5 0 0 0 4.5 11h5a1.5 1.5 0 0 0 .645-.148L4.293 5H3zM9.5 2A2.5 2.5 0 0 1 12 4.5v5c0 .12-.012.236-.028.35L11 8.88V5H7.121l-1-1h4.794A1.5 1.5 0 0 0 9.5 3H5.121l-.973-.973Q4.321 2.001 4.5 2z");
}

</style>
