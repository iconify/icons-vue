<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lw8ooyc2o"/><path clip-rule="evenodd" class="lg7s0v7-j"/><path clip-rule="evenodd" class="namlimbrc"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:person-checkmark-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.lg7s0v7-j {
  fill-rule: evenodd;
  d: path("M1 14.833c0-3.295 2.79-5.766 6.013-5.766c3.232 0 5.987 2.478 5.987 5.766V17a1 1 0 1 1-2 0v-2.167c0-2.08-1.753-3.766-3.987-3.766c-2.24 0-4.013 1.692-4.013 3.766l.002 2.166a1 1 0 0 1-2 .002zM18.597 4.126a1 1 0 0 1 .388 1.36l-2.777 5a1 1 0 1 1-1.749-.972l2.778-5a1 1 0 0 1 1.36-.388");
}

.lw8ooyc2o {
  fill-rule: evenodd;
  d: path("M7 5c-.792 0-1.5.679-1.5 1.6S6.208 8.2 7 8.2s1.5-.679 1.5-1.6S7.792 5 7 5M3.5 6.6C3.5 4.65 5.03 3 7 3s3.5 1.65 3.5 3.6s-1.53 3.6-3.5 3.6s-3.5-1.65-3.5-3.6");
}

.namlimbrc {
  fill-rule: evenodd;
  d: path("M11.775 7.153a1 1 0 0 1 1.405-.156l2.778 2.222a1 1 0 1 1-1.25 1.562l-2.777-2.222a1 1 0 0 1-.156-1.406");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
