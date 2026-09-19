<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><g class="y9tr6bcfx"><path class="j0ug10bgz"/><path class="zvdj6tbzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zhejiang-tax" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.j0ug10bgz {
  d: path("M19.048 17.077v14.627m-2.658-14.36c1.884-.106 3.456-.293 5.652-1.01m-5.806 4.826h5.623m-2.81.22A27 27 0 0 1 16 28.022m3.063-6.512c1.097 1.902 1.957 3.414 2.73 5.074m1.491-7.432h7.876v5.175h-7.876z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zvdj6tbzi {
  d: path("M32 27.49v2.753c0 .577-.465 1.043-1.043 1.043h-1.625c-.479 0-.716-.331-.716-.716v-6.267m-3.031.001c.088 3.609-1.135 5.897-3.98 7.05m2.78-14.964l1.306 2.761m4.565-2.855c-.512 1.166-1.087 1.923-1.726 2.849");
}

</style>
