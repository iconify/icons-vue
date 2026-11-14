<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4dm_ubrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ping-pong-edge-ball" /></template>
<style>
.n4dm_ubrd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 4.25q-3.75 0-3.75 3.75q0 1.378.507 2.25h-8.83q-1.391 0-2.013 1.244l-2 4q-.561 1.122.099 2.189q.659 1.067 1.914 1.067h12.146q1.391 0 2.013-1.244l2-4q.548-1.096-.069-2.14Q22.75 10.549 22.75 8q0-3.75-3.75-3.75m-5.25 6q.177 0 .335.079q.066.033.125.079q.058.045.107.101q.048.055.085.12q.036.064.06.134q.023.07.032.143t.004.147t-.025.145t-.052.137l-3.5 7q-.067.134-.18.232q-.112.097-.254.145q-.141.047-.29.036q-.149-.01-.282-.077q-.066-.033-.125-.079q-.058-.045-.107-.101q-.048-.055-.085-.12q-.036-.064-.06-.134q-.023-.07-.032-.143t-.004-.147t.025-.145t.052-.137l3.5-7q.047-.094.117-.171t.16-.132t.189-.083q.101-.029.205-.029");
}

</style>
