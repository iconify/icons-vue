<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj_0j2-jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:oil-barrel" /></template>
<style>
.uj_0j2-jd {
  fill: currentColor;
  d: path("M4.48 20q-.212 0-.356-.144t-.143-.357t.143-.356t.357-.143h1.211v-6.5H4.481q-.213 0-.356-.144t-.144-.357t.144-.356t.356-.143h1.211V5H4.481q-.213 0-.356-.144t-.144-.357t.144-.356T4.48 4H19.5q.213 0 .356.144t.144.357t-.144.356T19.5 5h-1.192v6.5H19.5q.213 0 .356.144t.144.357t-.144.356t-.356.143h-1.192V19H19.5q.213 0 .356.144t.144.357t-.144.356T19.5 20zm9.29-5.353q.73-.72.73-1.74q0-.813-.469-1.396T12 9.116q-1.548 1.803-2.024 2.395t-.476 1.4q0 1.018.729 1.736q.728.719 1.769.719t1.771-.72");
}

</style>
