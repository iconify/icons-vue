<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p_vr_6bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:music-note-off-2-16-regular" /></template>
<style>
.p_vr_6bjd {
  fill: currentColor;
  d: path("m12.553 13.26l1.593 1.594a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708L5 5.707v5.56A2 2 0 1 0 6 13V7.352l.475-.17l3.265 3.265a2 2 0 1 0 2.813 2.813m-.715-.715a.999.999 0 1 1-1.383-1.383zM4 12a1 1 0 1 1 0 2a1 1 0 0 1 0-2m8-7.852L7.777 5.656l.783.782L12 5.21v4.669l1 1V1.926a.8.8 0 0 0-1.07-.754L5.568 3.445l.782.783L12 2.209z");
}

</style>
