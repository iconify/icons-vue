<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm_8wkg3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:map-story" /></template>
<style>
.gm_8wkg3q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h10q1.76 0 3.005 1.245T21.25 6v12q0 1.76-1.245 3.005T17 22.25H7q-1.76 0-3.005-1.245T2.75 18V6q0-1.76 1.245-3.005T7 1.75m6.75 5.75q0 1.786 1.418 2.154q-.462 1.839-3.536 3.567Q7.25 15.686 7.25 18.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T8 19.5t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.186 3.618-4.221q3.886-2.186 4.326-4.843Q18.25 9.371 18.25 7.5q0-2.25-2.25-2.25T13.75 7.5");
}

</style>
