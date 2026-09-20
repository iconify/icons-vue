<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3l0dp-9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:replace-video-rounded" /></template>
<style>
.l3l0dp-9d {
  fill: currentColor;
  d: path("M8 21q-.671 0-1.143-.472q-.473-.472-.473-1.144v-6.768q0-.672.473-1.144Q7.329 11 8 11h6.77q.67 0 1.142.472t.472 1.144V15.5l1.92-1.92q.192-.191.444-.086t.252.379v4.273q0 .273-.252.37t-.444-.097l-1.92-1.919v2.885q0 .67-.472 1.143Q15.44 21 14.77 21zM19.192 8.77h-3.461q-.214 0-.357-.144t-.143-.357t.143-.357t.357-.143h2.361q-.84-1.725-2.49-2.747T12 4Q9.86 4 8.108 5.174t-2.53 3.124q-.119.25-.307.306t-.365-.023t-.267-.275t-.005-.367q.893-2.237 2.898-3.588T12 3q2.223 0 4.099 1.144T19 7.234V4.5q0-.213.143-.357T19.5 4t.357.143T20 4.5v3.462q0 .348-.23.578t-.578.23");
}

</style>
