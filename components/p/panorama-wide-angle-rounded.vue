<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p22-6pk_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-wide-angle-rounded" /></template>
<style>
.p22-6pk_c {
  fill: currentColor;
  d: path("M7.732 18.788q-2.032-.213-3.924-.672q-.43-1.495-.618-3.02Q3 13.568 3 12t.19-3.095t.618-3.02q1.84-.443 3.863-.664T12 5t4.329.221t3.863.664q.43 1.494.619 3.02T21 12t-.192 3.095t-.616 3.02q-1.892.46-3.924.673T12 19t-4.268-.213");
}

</style>
