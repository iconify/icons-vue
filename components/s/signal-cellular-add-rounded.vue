<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvq35im3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-add-rounded" /></template>
<style>
.kvq35im3h {
  fill: currentColor;
  d: path("M18.643 20.856q-.143-.143-.143-.356V18H16q-.213 0-.356-.144t-.144-.357t.144-.356T16 17h2.5v-2.5q0-.213.144-.356t.357-.144t.356.144t.143.356V17H22q.213 0 .356.144t.144.357t-.144.356T22 18h-2.5v2.5q0 .213-.144.356t-.357.144t-.356-.144M4.944 21q-.373 0-.593-.252t-.22-.55q0-.148.055-.294q.056-.146.187-.277L19.621 4.379q.131-.131.277-.187t.295-.055q.297 0 .55.22q.251.22.251.593v6.016q0 .373-.282.581q-.281.209-.649.136q-.29-.067-.567-.092T19 11.567q-2.47 0-4.201 1.732q-1.732 1.731-1.732 4.201q0 .66.144 1.299t.435 1.232q.168.348-.011.659q-.18.31-.537.31z");
}

</style>
