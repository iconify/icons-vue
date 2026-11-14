<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w554_1bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:portable-compressor" /></template>
<style>
.w554_1bph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.75 6.81q1.284.214 2.255 1.185Q16.25 9.24 16.25 11v4.217q2.847-.264 3.394-2.636q.227-.984-.164-1.71q-.334-.621-.98-.621q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014q1.542 0 2.301 1.41q.659 1.224.305 2.759q-.812 3.516-4.856 3.805V17q0 1.76-1.245 3.005T12 21.25H6q-1.76 0-3.005-1.245T1.75 17v-6q0-1.76 1.245-3.005q.971-.971 2.255-1.185V4.5q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 3.75 6 3.75h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-6-.06h4.5v-1.5h-4.5zM9 10q-4 0-4 4t4 4t4-4t-4-4");
}

</style>
