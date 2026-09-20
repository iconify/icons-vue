<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkjv35bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vr180-create2d-off-sharp" /></template>
<style>
.jkjv35bvv {
  fill: currentColor;
  d: path("M8 17.75q-2.675-.675-4.337-2.838T2 10q0-1.125.3-2.15t.825-1.925l-2.5-2.5l1.4-1.4L21.2 21.2l-1.4 1.4l-.6-.6H10v-9.2l-2-1.975zM10 2q2.75 0 4.913 1.663T17.75 8h-6.925L5.95 3.1q.925-.55 1.95-.825T10 2m2.825 8H22v9.175zm3.375 9l-.7-.725l-1.425-1.4L12.5 19z");
}

</style>
