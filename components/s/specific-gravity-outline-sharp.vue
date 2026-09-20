<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd8spzl6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:specific-gravity-outline-sharp" /></template>
<style>
.pd8spzl6y {
  fill: currentColor;
  d: path("M5.2 22L3 2h18l-2.2 20zm.475-14H9.35q.525-.475 1.2-.737T12 7t1.45.263t1.2.737h3.675l.425-4H5.225zM12 13q.825 0 1.413-.587T14 11t-.587-1.412T12 9t-1.412.588T10 11t.588 1.413T12 13m-6.1-3L7 20h10l1.1-10h-2.225q.05.25.088.488T16 11q0 1.65-1.175 2.825T12 15t-2.825-1.175T8 11q0-.275.038-.513T8.124 10zM7 20h1.125H8h8h-.125H17z");
}

</style>
