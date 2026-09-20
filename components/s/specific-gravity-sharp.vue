<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8mscwr8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:specific-gravity-sharp" /></template>
<style>
.g8mscwr8r {
  fill: currentColor;
  d: path("M5.2 22L3 2h18l-2.2 20zm.475-14H9.35q.525-.475 1.2-.737T12 7t1.45.263t1.2.737h3.675l.425-4H5.225zM12 13q.825 0 1.413-.587T14 11t-.587-1.412T12 9t-1.412.588T10 11t.588 1.413T12 13");
}

</style>
